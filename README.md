# AliPeace-AWS-Web-Application
 Learning how to deploy a web application with AWS
### Table of contents
    1) Steps on how to launch an EC2 instance
        1.1 Creation of Security group
        1.2 Creation of key pair
        1.3 Launching of an EC2 instance
        1.4 Installation of the Apache app 
        1.5 Verifying the Public IP Address tocheck if it is working
    2) List of all the AWS Services used and thier purpose

## Overview

This repository is the presentation of my project on how to launch 
an Ec2 instance, the steps i followed in launching the instance and 
the purpose of each AWS services used.

## 1) Steps on how to launch an EC2 instance

#### 1.1 Creation of Security group

Before the Creation of the Security group, i first changed the region
to ireland as specified in the instruction. (Note that before the Creation
of the Security group, you need to create the following; 1) Vpc, 2) subnets
3) An internet Gateway and 4) Network Access Control list. But due to the $$
that the limit for vpc creation was met, i couldn't create a vpc therefore allowing 
me to use the default one created by our tutor). 

steps;
1) I searched for EC2 instance and click on it, and then i searched for the network$ security seeting 
and clicked on security group.
2)  I then named my security group (alipeace_lita), i added a description to allow SSH and HTTP traffic.
3) I added the VPC created by our tutor.
4) Then under the inbound rule setting, i allowed the SSh(IPv4) and HTTP(IPv4).
5) i then checked if my data was correct and created the security group.

![A screenshot of a security group that was successfuly created]{security group.png}



