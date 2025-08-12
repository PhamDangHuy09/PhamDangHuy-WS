---
title : "Create role"
date : "`r Sys.Date()`"
weight : 2
chapter : false
pre : " <b> 2.1.2 </b> "
---

#### Create Role 

1. Go to [IAM service management console]
  + Click **Role**.
  + Click **Create role**.

![VPC](/images/2.prerequisite/003-createsubnet.png)

2. At the step 1 **select trusted enity** page.
  + In the **Service or use case** select **EC2**.
  + Click **Next**.

![VPC](/images/2.prerequisite/004-createsubnet.png)


1. At the step 2 **Add permissions**.
  + In the **Permissions policies** Click **AmazoneEC2ContainerRegistryFullAccess**.
  + Click **Next**.

![VPC](/images/2.prerequisite/005-createsubnet.png)

1. At the step 3 **Name,review, and create**.
  + In the **Role name**  field, enter **batch-yt-role**
  + Click **Create role**

![VPC](/images/2.prerequisite/006-createsubnet.png)