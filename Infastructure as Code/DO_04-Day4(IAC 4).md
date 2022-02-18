
1. What is AWS CloudFormation?<br>
	AWS CloudFormation is a service that gives developers and businesses an easy way to create a collection of related AWS and third-party resources, and provision and manage them in an orderly and predictable fashion.


2. What are the main components in CloudFormation (CF)?<br>
	A CloudFormation template consists of 6 sections – Description, Parameters, Mappings, Conditions, Resources and Outputs.


3. What is the cost of using (CF)?<br>
	There is no additional charge for AWS CloudFormation. You pay for AWS resources (for example, Amazon EC2 instances, Elastic Load Balancing load balancers, and so on) created using CloudFormation as if you created them by hand.


4. What is the visual tool offered by (CF)?<br>
AWS CloudFormation Designer is a graphic tool for creating, viewing, and modifying AWS CloudFormation templates. With Designer, you can diagram your template resources using a drag-and-drop interface, and then edit their details using the integrated JSON and YAML editor.


5. Are (CF) Templates Declarative or Imperative?<br>
	Declarative


6. Give examples of items that can be included in a CF template.<br>
Transform, Description, Resources, Type, Properties, Handler, Runtime, Events, Path, Method


7. What is produced by a CF Template?<br>
	A stack
	

8. Which one of the following operations can you perform on a CF Stack?<br>
	a) Create Stack<br>
	b) Add New Items to Stack<br>
	c) Remove Items from Stack<br>
	d) Edit Stack<br>
	e) Tear Down Stack<br>

	All of the above


9. What are the three ways of creating a Stack?<br>
	‘aws cloudformation create-stack’ for CLI<br>
	In the AWS console<br>
	CloudFormation API<br>


10. What are the main components of CF Designer UI?<br>
	Toolbar, Resource types pane, Canvas pane, Fit to window button, Full screen and Split screen buttons, Integrated JSON and YAML editor pane, and Messages pane


11. What are the Resource Types you can’t include in the designer?<br>
	DELETE_IN_PROGRESS or DELETE_COMPLETE


12. Does CF designer auto save templates?<br>
	It doesn’t auto save


13. Can you download the CF template design as image and how?<br>
    - Step 1: Download the Template
    - Step 2: Create a Key Pair
    - Step 3: Create a Portfolio
    - Step 4: Create a Product
    - Step 5: Add a Template Constraint
    - Step 6: Add a Launch Constraint
    - Step 7: Grant End Users Access to the Portfolio
    - Step 8: Test the End User Experience


14. What script formats can you product CF templates?<br>
	json and yaml


15. Name 5 items in a high level template structure?<br>
    - Description
    - Parameters
    - Resources
    - Outputs
    - AWSTemplateFormatVersion


16. Describe CF “Changeset”.<br>
When you need to update a stack, understanding how your changes will affect running resources before you implement them can help you update stacks with confidence. Change sets allow you to preview how proposed changes to a stack might impact your running resources, for example, whether your changes will delete or replace any critical resources, AWS CloudFormation makes the changes to your stack only when you decide to execute the change set, allowing you to decide whether to proceed with your proposed changes or explore other changes by creating another change set. You can create and manage change sets using the CloudFormation console, AWS CLI, or CloudFormation API.


17. Describe CF “Termination Policy”.<br>
You can prevent a stack from being accidentally deleted by enabling termination protection on the stack. If a user attempts to delete a stack with termination protection enabled, the deletion fails and the stack, including its status, remains unchanged. You can enable termination protection on a stack when you create it. Termination protection on stacks is disabled by default. You can set termination protection on a stack with any status except DELETE_IN_PROGRESS or DELETE_COMPLETE.


18. Describe CF Drift Detection and Drift Analysis.<br>
    - CloudFormation gives you the tool to detect drift in your infrastructure over time. You can use this tool to view the changes both in terms of the AWD components and a visual representation of the changes to the template.
    - Performing a drift detection operation on a stack determines whether the stack has drifted from its expected template configuration, and returns detailed information about the drift status of each resource in the stack that supports drift detection.

