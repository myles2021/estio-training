

1. Describe why IaC is important in DevOps lifecycle. 
    - Ability to provision infrastructure on demand as code, removing a transitional bottleneck in software development lifecycle.
    - Ability to automate the process which is the fundamental tenet of DevOps.



2. List the 5 benefits of IaC in DevOps lifecycle. 
    - Ability to configure the newly provisioned Infrastructure as Code (IaC).
    - Ability to test IaC before deployment reducing mishaps.
    - Ability to revision the IaC.
    - Ability to control cost on Pay-as-you-go basis.
    - Ability to deploy the same IaC on different providers’ platforms.


3. Name two virtualisation scenarios. 
    - Virtualisation
        - Virtualisation creates a simulated, or virtual computing environment imitating a physical environment.
    - VMs
        - Virtual Machines (VMs) are also computer generated environments imitating a physical machine. An application software is responsible for creating virtual machines with Processors, Memory, Networking, Storage etc in which we can install OS and configure the machines. Once a VM is made available to you connect to it and use it as if it was a real machine. 


4. Explain the difference between Host and Guest Computers. 
    - The host operating system is software installed on a computer to interact with the hardware, the guest operating system is software installed onto and running on the virtual machine.


5. What is a hypervisor? 
    - Hypervisors create an abstraction layer over computer hardware (Host computer) and host Operating System allowing the hardware elements of a single computer (processors, memory, storage etc) to be shared by multiple virtual computers (Guest computers), commonly called Virtual Machines (VMs). 


6. Name different types of hypervisors. 
    - Type 1 hypervisor:
        - VM & OS
        - Type 1 hypervisor
        - Physical server (Hardware)
    - Type 2 hypervisor:
        - VM & OS
        - Type 2 hypervisor
        - Operating System
        - Physical server (Hardware)


7. Name examples of different hypervisors. 
    - Type 1 hypervisor:
        - VMWare vSphere ESXi
    - Type 2 hypervisor:
        - Oracle VirtualBox


8. Describe deployment automation. 
    - Deployment automation provides the ability to move your software between testing and production environments by using automated processes. ... Deployment automation lets you release new features and applications more quickly and frequently, while removing the need for human intervention in application deployments.


9. Describe configuration management. 
    - Configuration management is a systems engineering process for establishing and maintaining consistency of a product's performance, functional, and physical attributes with its requirements, design, and operational information throughout its life.
    - It will configure your instances, your VMs etc.


10. Name some of the DevOps automation challenges. 
    - How can we repeat the same process while preventing potential human errors? 
    - How can we make minor changes to the machine configuration and replicate the same across many sites and teams?
    - How can we produce hundreds or event thousands of the duplicate VMs and configurations while avoiding the unnecessary manual work?
    - After a while, having created multiple versions of the VM and the web server, how can we roll back to previous configuration?
    - How can we monitor the configuration mutation over time?


11. What is Vagrant and why is it useful for DevOps teams? 
    - Vagrant is an open-source utility created by Hashicorp (same people who’ve created Packer and Terraform).
    - Vagrant is a wrapper utility that works on top of Virtual Machine providers like VirtualBox, Hyper-V, VMware, and also Docker. 
    - Vagrant abstracts away the complex activities involved in managing a VM and it can also work with provisioners like Chef, Puppet, Shell and custom methods to automate most of the tasks.
    - One of the best tools for conceptualisation of IaC.
    - Ideal Learning Lab for IaC setup.
    - Automation of providers and provisioners instructions.
    - Transferrable and version controlled scripts.
    - Repeatable across teams and environments.
    - Can work with multiple ‘Providers’.
    - Can work with multiple ‘Provisioners’.
    - Can package the end product for distribution .


12. What is a Vagrant “Provider”? 
    - Vagrant is a wrapper utility that works on top of Virtual Machine providers like VirtualBox, Hyper-V, VMware, and also Docker. 


13. What is a Vagrant “Provisioner”? 
    - Provisioners in Vagrant allow you to automatically install software, alter configurations, and more on the machine as part of the vagrant up process.


14. Name 4 Vagrant provisioners. 
    - Chef, Puppet, Shell, and Ansible.


15. What is Vagrant Cloud used for? 
    - Vagrant Cloud is a hosted service for finding boxes, sharing boxes, managing Vagrant Shares.


16. What is a Vagrantfile? 
    - The Vagrantfile is a Ruby file used to configure Vagrant on a per-project basis. The main function of the Vagrantfile is to described the virtual machines required for a project as well as how to configure and provision these machines.


17. How is a Vagrantfile created? 
    - vagrant init


18. What is the mechanism for executing Vagrantfile instructions? 
    - vagrant up


19. Name 4 providers Vagrant can use? 
    - VirtualBox
    - VMware
    - Hyper-V
    - AWS
    - Docker Virtualisation ship


20. What is a declarative configuration model? 
    - Declarative focuses on what.
    - In a software engineering context, declarative programming means writing code to describe what the program should do as opposed to how it should do it.
    - Describes what needs to happen; the specifics for making it so are left to the system.


21. What is an imperative configuration model? 
    - Imperative focuses on how. 
    - In a software engineering context, imperative programming means writing code to describe how the program should do what is designed to do. 
    - This involves writing code that follows explicit steps to solving a problem, completing a task, or achieving a desired result. It’s telling the system specifically how to do something with the expectation that the desired outcome will result.


22. Using Vagrant create an infrastructure with one Virtual Machine with the following hardware / network / storage configuration: 

a) Name this machine “iac-day1” 

b) Base Memory 2048 

c) Processors 2 

d) 32 GB Storage 

e) Bridged Network Adapter 

f) You may accept the default parameters. 

g) Challenge: Experiment with other machine setup parameters 



23. Install Apache2 on “iac-day1”. 

a) In the first instance install Apache2 manually. 

b) Repeat the last step but this time use a bash script to install Apache2 

c) Change your last step to include creation custom index.html with the message – “hello [your name]”. The exercise is to create the index.html from the bash script. 

d) Make your Apache2 index.html accessible from outside world – 

e) Request Apache2 index.html from your host browser. 



24. Present your breakout team work to the class and discuss your experience: 

a) Possible issues you had to resolve in creating the box 

b) Possible issues you had to resolve in setting up the web server, index.html and making it available to outside world.
