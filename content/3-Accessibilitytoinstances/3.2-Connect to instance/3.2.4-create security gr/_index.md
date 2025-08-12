---
title : "Create Security Group"
date : "`r Sys.Date()`"
weight : 3
chapter : false
pre : " <b> 3.2.3 </b> "
---



1. Go to [EC2 service management console]
  + Click **EC2 Dashboard**.
  + Click **Security Groups**
  + Click **Create Security Groups**.

![Connect](/images/3.connect/027-ec2role.png)

2. At the Create security group
  + in the Security group name field, enter**batch-compute-sg**
  + in the description field, enter **SG for Batch service**
  + Click **Create security group**
![Connect](/images/3.connect/027-ec2role.png)

3. Go to [IAM service management console]
   + At the Role page
   + CLick Create Role
   + At the step 1: In the Use Case select **Elastic Container Service Task** and click next
   + At the step 2: in the permissions policies select **AmazonS3FullAccess** and click next
   + At the step 3: in the Role name field, enter **batch-yt-ecs-role** and click create role.