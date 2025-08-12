---
title : "Compute environments"
date : "`r Sys.Date()`"
weight : 1
chapter : false
pre : " <b> 4.1 </b> "
---


1. Go to [AWS Batch service management console]
  + Click **Compute Enviroments**.
  + Click **Create**
  + At the step 1: in the Name field, enter **yt-s3-copy** and click next
  + At the step 2: int Maxinum vCPUs field, enter **10** and click next
  + At the step 3: click next
  + At the step 4: click Create compute environment
  + Click on the **SSM-Role** role.

![S3](/images/4.s3/002-s3.png)

1. Click **Attach policies**.
 
![S3](/images/4.s3/003-s3.png)

3. In the Search box enter **S3**.
  + Click the policy **AmazonS3FullAccess**.
  + Click **Attach policy**.
 
![S3](/images/4.s3/004-s3.png)
 
{{%notice tip%}}
In the production environment, we will grant stricter permissions to the specified S3 bucket. In the framework of this lab, we use the policy **AmazonS3FullAccess** for convenience.
{{%/notice%}}

Next, we will proceed to create an S3 bucket to store session logs.