1. Question 1 of 40 <br>
    1. What is your responsibility in terms of cloud security: 
        1. Operating System, Network & Firewall Configuration 


2. Question 2 of 40 <br>
    1. Match the options below: 
        1. Cluster of availability zones -> Regions
        2. Contains one or more data centres -> Availability zones 
        3. The backbone of cloud infrastructure -> Data Centres 
        4. Allow content to be cached for lower latency -> Points of Presence 


3. Question 3 of 40 <br>
    1. Ansible configuration files are in YAML 
        1. True 


4. Question 4 of 40 <br>
    1. Match the options below: 
        1. Blocks -> Containers for other content and usually represent the configuration of some kind of object, like a resource. 
        2. Assigns a value to a name. -> Arguments 
        3. Represents a value. -> Expressions 


5. Question 5 of 40 <br>
    1. What is the equivalent to CloudFormation? 
        1. Ansible and Terraform 


6. Question 6 of 40 <br>
    1. You cannot review changes with execution plans in Terraform. 
        1. False 


7. Question 7 of 40 <br>
    1. What keeps track of the infrastructure in Terraform? 
        1. State file 


8. Question 8 of 40 <br>
    1. Match the Terraform commands below: 
    2. Prepare your working directory for other commands -> init 
    3. Check whether the configuration is valid -> validate 
    4. Show changes required by the current configuration -> plan
    5. Create or update infrastructure -> apply 
    6. Destroy previously-created infrastructure -> destroy 


9. Question 9 of 40 <br>
    1. Relational Database -> Amazon Aurora 
    2. Key-Value Database -> Amazon DynamoDB 
    3. In-memory Database -> Amazon ElastiCache for Redis 
    4. Document Database -> Amazon DocumentDB 
    5. Wide Column Database -> Amazon Keyspaces 
    6. Graph Database -> Amazon Neptune 
    7. Time Series Database -> Amazon Timestream 
    8. Ledger Database -> Amazon Quantum Ledger Database 


10. Question 10 of 40 <br>
    1. How durable is AWS S3 Storage? 
        1. 99.999999999% (11 nines)


11. Question 11 of 40 <br>
    1. Which of the following best describes Lambda: 
        1. Serverless and a Function as a Service 


12. Question 12 of 40 <br>
    1. laas benefits include: 
        1. Not having to worry about the underlying hardware 
        2. Controlling the cost through usage and interaction alerts 


13. Question 13 of 40 <br>
    1. Which of the below is the way to write comments in Terraform: 
        1. # 
        2. // 
        3. /* and *1 


14. Question 14 of 40 <br>
    1. Which is correct: 
    2. Correct answer: A. Selected answer: A.
        1. A. module "first_module" { 
		source = "/module-1" resource_name = some_resource.example.name 
        1. B. module "first module" ( 
		source = "./module-1" resource_name = some_resource.example.name 
        1. C. module first_module { 
	source = /module-1 resource_name = some_resource.example.name 
        1. D. module { 
		source = "/module-1" resource_name = some_resource.example.name 


15. Question 15 of 40 <br>
    1. Where are the hosts listed? 
        1. inventory.yaml 


16. Question 16 of 40 <br>
    1. Which is correct: 
    2. Correct answer: A. Selected answer: A. 
        1.  A. resource "aws_vpc" "main" { 
        2. 		cidr_block = var.ba	se_cidr_block 
        3. B. resource "aws_vpc" { 
        4. 		cidr_block = var.base_cidr_block 
        5. C. resource "aws_vpc" "main" { 
        6. 		cidr_block = base_cidr_block 
        7. D. resource "aws_vpc" "main" ( 
        8. 		cidr_block = var.base_cidr_block 
        9. E. resource "aws_vpc" "main" { 
        10. 		cidr_block == var.base_cidr_block 



17. Question 17 of 40 <br>
    1. Which of the following are examples of NoSQL databases: 
        1. A. Key-value 
        2. B. Document 
        3. C. Graph 
        4. D. In-memory 
        5. All of the above (CORRECT)



18. Question 18 of 40 <br>
    1. What is the cloud platforms responsibility: 
        1. Storage 



19. Question 19 of 40 <br>
    1. Which statement best explains PaaS: 
        1. It removes the control of the underlying infrastructure. 
        2. It allows you to build your own applications. 


20. Question 20 of 40 <br>
    1. S3 Bucket naming convention: 
        1. No uppercase 
        2. No underscore 
        3. Must start with lowercase letter or number 


21. Question 21 of 40 <br>
    1. Gmail is a Saas 
        1. True 


22. Question 22 of 40 <br>
    1. ‘count’ can be used with modules and with every resource type. 
        1. True 


23. Question 23 of 40 <br>
    1. Match the options below: 
        1. Saas -> We'll take care of it all 
        2. Paas -> Here's the tools to make stuff 
        3. laaş -> It's all your responsibility 


24. Question 24 of 40 <br>
    1. CloudFormation can perform as Provider and Provisioner 
        1. True 

 
25. Question 25 of 40 <br>
    1. ‘count’ can accepts numbers that aren't whole numbers e.g. 2.5 
        1. False 


26. Question 26 of 40 <br>
    1. Terraform does not allow you to define resources and infrastructure 
        1. False 
	


27. Question 27 of 40 <br>
    1. What is Microsoft's equivalent to AWS CloudFormation? 
        1. Azure Resource Manager 
	

28. Question 28 of 40<br>
    1. Terraform is: 
        1. Declarative, not procedural 
	

29. Question 29 of 40<br>
    1. The source argument is mandatory for all modules 
        1. True 
	
30. Question 30 of 40 <br>
    1. Microsoft 365 is a Paas 
        1. False 
	

31. Question 31 of 40 <br> 
    1. Which of the following are global services: 
        1. Route 53 


32. Question 32 of 40 <br> 
    1. Match the protocol to the port number below: 
        1. 22 -> SSH
        2. 21 -> FTP
        3. 22 -> SFTP
        4. 80 -> HTTP
        5. 443 -> HTTPS
        6. 3306 -> MySQL
        7. 3389 -> RDP



33. Question 33 of 40 <br> 
    1. Match the options below: 
        1. Scaling out -> Adding more servers 
        2. Scaling up -> Adding more RAM and CPUs 


34. Question 34 of 40 <br> 
    1. Match the options below: 
        1. contains the resources  -> main.tf 
        2. contains the variables used in the module -> variables.tf 
        3. contains the outputs produced by the module -> output.tf 


35. Question 35 of 40 <br> 
    1. Amazon RDS (Relational Database Service) is a Saas 
        1. False 


36. Question 36 of 40 <br> 
    1. Security groups only contain rules 
        1. True 


37. Question 37 of 40<br>  
    1. Unlike most of the CM tools Ansible isn't "push" based 
        1. False 
	
	
38. Question 38 of 40 
    1. Which of the following services are region scoped: 
        1. Elastic Beanstalk 


39. Question 39 of 40 
    1. Ansible isn't agentless 
        1. False 


40. Question 40 of 40 
    1. Terraform's configuration files are in .yaml file format. 
        1. False 
	
