# rean_assignment
Approach:
Changes are made here to demostrate Jenkins-GitHub Webhook Functionality
--Master Branch is usually the most stable branch, as such, as Jenkins should pull only when codes are committed to the Master Branch. Date needs to be updated.
1.	I used vagrant to spin up a centos 7 virtual machine
2.	I used Cloudformation to create AWS Resources which include a Amazon Linux EC2 Instance
3.	I logged into the EC2 instance using SSH
4.	Ansible was installed inside the EC2 instance 
5.	I used ansible playbook to download wordpress
