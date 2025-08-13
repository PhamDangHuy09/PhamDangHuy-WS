---
title : "Create EC2 Instance"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 2.1.1 </b> "
---


#### Create EC2 Instance **Lab EC2 Instance**
1. Go to [EC2 service management console]
   + Click **Instance**.
   + Click **Launch instance**.

![EC2 Instance](static/images/2.prerequisite/EC2.png)
![EC2 Instance](static/images/2.prerequisite/CreateInstance.png)

2. At the **Launch an instance** page.
   + In the **Name and tag** field, enter **Docker-Instance**.
   + In the **Amazon Machine Image** select: **Amazon Linux 2 AMI**.
   + In the **Key Pair** select: **Linux-KP** .
   + In the **Network Setting** select: **Select existing security group**.
   + Click **Launch instance**.

![EC2 Instance](/images/2.prerequisite/002-createvpc.png)