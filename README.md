# bob

Provide name (s)  of the Continuous Integration tools on which you have experience ?
i have experience with jenkins

Provide name (s) of the Continuous Deployment tools on which you have experience?
Docker , K8s

What all scripting languages do you know?
bash shell and ansible playbook

What all source code management systems have you worked with?
work with Git

Why is Ansible a preferred scripting construct for automation?
cause ansible has the power to target multiple server at the same time , via ssh

Explain in brief about the ansible master set up?
1 you install ansible
2 cd /etc/ansible
3 you add user ansible in group user for full access
4 you create ssh key and copy the key
5 you modify your host file
6 you ping your host to see if connected
7 start create ansible playbook

What software problems does IaC(Infra as Code) adresses?
The first big problem is cost. You’d have to hire many professionals to perform the necessary tasks at each step of the process, from network engineers to hardware maintenance technicians.

The next big problems are scalability and availability. But in the end, it all comes down to speed. Since manual configuration is so slow, applications would often struggle with spikes in access, while the system administrators would be desperately trying to set up servers to manage the load. This necessarily impacts availability. If the organization didn’t have backup servers or even data centers, then the application could be unavailable for long periods.

Explain components of Ansible automation engine. ?

Ansible is a radically simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs.

Ansible components
Inventory. The “inventory” is a configuration file where you define the host information. ...
Playbooks. In most cases – especially in enterprise environments – you should use Ansible playbooks. ...
Plays. Playbooks contain plays. ...
hosts
Tasks. ...
Roles. ...
Handlers. ...
Templates. ...
Variables.
Service
Name
Etc.. and all other module

How do you balance Load between servers in AWS?
Select a Load Balancer Type. ...
1.	Define Your Load Balancer. ...
2.	Assign Security Groups to Your Load Balancer in a VPC.
3.	 Configure Health Checks for Your EC2 Instances. 
4.	Register EC2 Instances with Your Load Balancer. 
5.	Tag Your Load Balancer  etc..
What are the various ways in which build can be scheduled in Jenkins?
u can trigger via poll scm(schedule your jod in a cron format) your job to build anytime the code modify.. or u can build periodically , and u put your schedule as a cron format,  create a pipeline with all the stages..or you build your job via jenkinsfile.

What is the use of JENKINS HOME directory?
The Jenkins home directory contains a subdirectory for each Jenkins build job being managed by this instance of Jenkins. Each job directory, in turn, contains two subdirectories, builds and workspace, along with some other files. It contains the build job config.xml file, which contains, as you might expect, the configuration details for this build job.

What is the command Kubectl and its syntax?
Kubectl is a command line tool for controlling Kubernetes clusters. kubectl looks for a file named config in the $HOME/.kube directory.  

syntax: we usually use those syntax to execute the kubectl commend ex; create, get, describe, delete etc..



What are Kubernetes Pods?
Pods are the smallest deployable units of computing that can be created and managed in Kubernetes.


What are the different software branching strategies?
Release Branching. ...
Feature Branching. ...
Story or Task Branching. ...
Manual Code Review and Merge. ...
Minimal Continuous Integration. ...
Continuous Integration etc...

Provide name of Artifact Repository tools on which you have experience? There’s many like Sonatype Nexus etc..
i have experience with maven
 
 thank you so mush , it was a litlle challenging

best regards
 

