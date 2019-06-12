# Ansible

**Installing Ansible!!!**

Prerequisites

AWS EC2 Instance( please select the Red hat Linux)
Provision two Redhat linux Instances.( Master & Salve) 

Installation steps:

1. Update your EC2 Instance: (Only in Master Node)
   >> yum update

2. Add a third party repository EPEL(Extra Package for Enterprize Linux) (Only in Master Node)

   >> rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
   
3. Install Ansible (Only in Master Node)

   >> yum install ansible -y 

4. Check "Ansible" Version (Only in Master Node)
   >> ansible --version
   

**Setup Inventory File**
1. Create a file named hosts-dev in the location /home/ec2-user
   >> cd /home/ec2-user
2. create a file named hosts-dev
   >> vi hosts-dev
   paste the content available in hosts-dev file
3. list our servers
   >> ansible --lists-hosts all
4. 
