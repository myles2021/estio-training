1. Explain the following Terraform CLI commands:

    1. init: this initialises your terraform file, the first step of CLI deployment 
    2. get: used to download and update modules  
    3. plan: this creates an execution plan, which lets you preview the changes that Terraform plans to make to your infrastructure. 
    4. apply: this executes the actions proposed in a Terraform plan. 
    5. destroy: this destroys all remote objects managed by a particular Terraform configuration. 
    6. login: this can be used to automatically obtain and save an API token for Terraform Cloud, Terraform Enterprise, or any other host that offers Terraform services. 
    7. logout: this is used to remove credentials stored by terraform login 
    8. console: this provides an interactive console for evaluating expressions. 
    9. fmt: after upgrading Terraform, run terraform fmt on your modules along with any other changes you are making to adopt the new version. This is used to rewrite Terraform configuration files to a canonical format and style. This command applies a subset of the Terraform language style conventions, along with other minor adjustments for readability. 
    10. validate: this validates the configuration files in a directory, referring only to the configuration. 
    11. graph: this is used to generate a visual representation of either a configuration or execution plan. The output is in the DOT format, which can be used by GraphViz to generate charts. 
    12. output: this is used to extract the value of an output variable from the state file. 
    13. show: this is used to provide human-readable output from a state or plan file. This can be used to inspect a plan to ensure that the planned operations are expected, or to inspect the current state as Terraform sees it.

    14. import: this is used to import existing resources into Terraform. 
    15. state: this is used for advanced state management. 
    16. refresh: this reads the current settings from all managed remote objects and updates the Terraform state to match. 
    17. providers: this shows information about the provider requirements of the configuration in the current working directory, as an aid to understanding where each requirement was detected from. 
    18. version: this shows what version of terraform is being used and all installed plugins. 
    19. workspace: this is used to manage workspaces. 

2. What is the main directory of publicly available Terraform providers?
    - Terraform registry 

3. After which command does Terraform CLI finds and installs providers?
    - terraform init


4. What is a resource?
    - Resources are the most important element in the Terraform language. Each resource block describes one or more infrastructure objects, such as virtual networks, compute instances, or higher-level components such as DNS records. Resource Blocks documents the syntax for declaring resources.


5. What is a provider?
    - The provider meta-argument specifies which provider configuration to use for a resource, overriding Terraform's default behaviour of selecting one based on the resource type name


6. Name all 5 meta-arguments: 
    - depends_on
    - count
    - for_each
    - provider
    - lifecycle


7. Name 3 providers:
    - Google
    - AWS
    - Azure
    - Kubernetes
    - Oracle


8. Name 3 types of variables and outputs:
    - environment
    - region
    - ami_id


9. Explain what a module is:
    - A Terraform module is a set of Terraform configuration files in a single directory. Even a simple configuration consisting of a single directory with one or more .tf files is a module. When you run Terraform commands directly from such a directory, it is considered the root module. A Terraform module allows you to create logical abstraction on the top of some resource set. In other words, a module allows you to group resources together and reuse this group later, possibly many times


10. Which meta-arguments can be used with modules?
    - depends_on
    - count
    - for_each
    - provider
    - lifecycle


11. What is the difference between a root module and a child module?
    - Every Terraform configuration has at least one module, known as its root module, which consists of the resources defined in the . tf files in the main working directory. A module that has been called by another module is referred to as a child module.


12. Which argument do all modules require?
    - All modules require a source argument, which is a meta-argument defined by Terraform. Its value is either the path to a local directory containing the module's configuration files, or a remote module source that Terraform should download and use.


13. Name the 3 files you will find in a Terraform working directory or module:
    1. Variables
    2. Outputs
    3. Main 


14. What is Terraform Cloud?
    - Terraform Cloud is HashiCorp's managed service offering that eliminates the need for unnecessary tooling and documentation to use Terraform in production. Provision infrastructure securely and reliably in the cloud with free remote state storage.

1. What is the Core Terraform Workflow?
    - The core Terraform workflow has three steps: 
        1. Write - Author infrastructure as code. 
        2. Plan - Preview changes before applying. 
        3. Apply - Provision reproducible infrastructure.
