# Associate-Cloud-Engineer
Kategori : EN - Setting up a cloud solution environment 1

For the last three months, your company has been working on an application that deployed in an App Engine and it resides in the Dev Project. The app has completed the required testing and is ready to roll out to production. Your manager has asked you to create a new project to serve as your production environment. You want do the job done in as few as possible step. What should you do?

A
Deploy your application again using gcloud and specify the project parameter with the new project name to create the new project.

B
Use gcloud to create the new project and to copy the deployed application to the new project.

C
Create a Deployment Manager configuration file that copies the current App Engine deployment into a new project.

D
Use gcloud to create the new project, and then deploy your application to the new project.

1
Kategori : EN - Setting up a cloud solution environment 1

What is the correct command to set the default zone for Compute Engine VM using gcloud CLI?

A
gcloud config set compute/zone us-east1

B
gcloud config configurations set compute/zone us-east1-a

C
gcloud config set compute/zone us-east1-a

D
gcloud defaults set compute/zone us-east1

1
Kategori : EN - Setting up a cloud solution environment 1

While working on a project, an application administrator has been given the responsibility of managing all resources. He wants to delegate the responsibility of managing the existing service accounts to another administrator. He will also be responsible to manage the other service accounts that will be created. Which of the following is the best way to delegate the privileges required to manage all the service accounts?

A
Granting iam.serviceAccountUser to the administrator at the project level

B
Granting iam.serviceProjectAccountUser to the administrator at the project level

C
Granting iam.serviceAccountUser to the administrator at the service account level

D
Granting iam.serviceProjectAccountUser to the administrator at the service account level

1
Kategori : EN - Setting up a cloud solution environment 1

You are currently working on a freelance project where you have to deploy a WordPress website on VM. You decided to use a startup script to install WordPress and other libraries instead of manual installation. While launching you forgot to use the startup script and are wondering how to do it now. What should you do?

A
Edit the instance by selecting it, add metadata with the script as key, add script content as value, and restart the instance.

B
Edit the instance by selecting it, add your startup script to the user data field, and restart your instance.

C
Stop the instance, add metadata with startup-script as key, and script content as value, and start the instance.

D
Stop the instance, add a script into the startup script field, and start the instance.

1
Kategori : EN - Setting up a cloud solution environment 1

Your company has decided to build an in-house application for payroll processing, and you have been assigned a task to create a VM, Cloud SQL DB, and Cloud Storage bucket. While testing the application, developers found that they couldn't upload files to the bucket. You want to follow Google-recommended practices. What should you do?

A
Create a service account and add it to the IAM role 'storage.objectAdmin' for that bucket.

B
Create a service account and add it to the IAM role 'storage.objectCreator' for that bucket.

C
Check if egress firewall rules are applied to instances allowing connection between bucket and VM.

D
Check if the default service account is attached to VM, if not edit the instance and attach it.

1
Kategori : EN - Setting up a cloud solution environment 1

As per your manager's instruction, you created a custom VPC with a subnet mask of 24 which provides 256 IP addresses, but are only able to use 252 addresses out of it. Your manager is trying to figure out what's going wrong and approaches you for the answer. What will you answer to your manager?

A
GCP reserves four IP addresses in each primary subnet range, because of which the usable IP count is 252.

B
Just tell the manager that it's the rule when networking in GCP.

C
It's because your account has reached a soft limit for the number of private IP address spaces. Raise a request for a quota increase.

D
Inform the manager that you will recreate the VPC because you feel something went wrong while creating a subnet.

1
Kategori : EN - Setting up a cloud solution environment 1

Your company has 5 TB of testing data stored in the production database of a testing tool name Quality Center. The data is being used to create a real-time analytics system which is causing a slow response to the tester while using the tool. What should you do the improve the load on the database?

A
Scale the database instance.

B
Set up Multi-AZ.

C
Run the analytics query only on weekends.

D
Set up a read replica.

1
Kategori : EN - Setting up a cloud solution environment 1

You built an application on Google Cloud that uses Cloud Spanner. Your support team needs to monitor the environment but should not have access to table data. You need a streamlined solution to grant the correct permissions to your support team, and you want to follow Google-recommended practices. What should you do?

A
Add the support team group to the roles/spanner.databaseUser role.

B
Add the support team group to the roles/monitoring.viewer role.

C
Add the support team group to the roles/spanner.databaseReader role.

D
Add the support team group to the roles/stackdriver.accounts.viewer role.

1
Kategori : EN - Setting up a cloud solution environment 1

There is a requirement to develop a Prototype for an OCR (Optical Character Recognition) based Expense management application. It should ideally have the functionality of scanning receipts and extracting textual data. You have a very small team and also have to deliver the project's prototype on a quick timeline. Which of the following approaches can be adopted to implement the requirement?

A
Assign the OCR application development work to an in-house Data Science team to model the data in a customized way with training and prediction services using the GCP AI platform.

B
Use the Vision API and use pre-trained data models.

C
Use Cloud Data flow for streaming data pipelines.

D
Use Vertex Al to model the data and leverage the features of AutoML.

1
Kategori : EN - Setting up a cloud solution environment 1

You need to produce a list of the enabled Google Cloud Platform APIs for a GCP project using the gcloud command line in the Cloud Shell. The project name is my-project. What should you do?

A
Run gcloud info to view the account value, and then run gcloud services list --account <Account>.

B
Run gcloud init to set the current project to my-project, and then run gcloud services list --available.

C
Run gcloud projects list to get the project ID, and then run gcloud services list --project <project ID>.

D
Run gcloud projects describe <project ID> to verify the project value, and then run gcloud services list --available.

1
Kategori : EN - Planning and configuring a cloud solution 1

You work for a retail company that has a busy online store. As you are approaching New Year, you find that your e-store is getting more and more traffic. You ensure that your web servers are behind a managed instance group. However, you notice that the web tier is frequently scaling, sometimes multiple times in an hour. You need to prevent the instance group from scaling up and down so rapidly. Which of the following options would help you to achieve this?

A
Change the auto-scaling metric to use multiple metrics instead of just one metric.

B
Reduce the maximum instance count.

C
Associate a health check with the instance group.

D
Increase the cooldown period.

1
Kategori : EN - Planning and configuring a cloud solution 1

You are one of the Cloud Engineers in an Enterprise level tech company. You have been given the task to come up with a plan to run complex workloads that need flexibility and control at the configuration level with high memory and processing power. The workloads are planned to run for the next 6 months. Choose the cost-effective option to achieve the best performance for a specific workload.

A
Choose App Engine to run the workload and reduce the complexity.

B
Choose Compute Engine VMs with predefined types and use templates from the GCP marketplace.

C
Choose Cloud Run to fetch Docker images from Container Registry and run the workload.

D
Choose Compute Engine with custom machine types and select the required number of vCPUs and gigabytes of memory.

1
Kategori : EN - Planning and configuring a cloud solution 1

You have set a firewall rule that will permit inbound connections to a VM instance named dev-server-2. You want to apply this rule only if there is no other rule that would deny that traffic. What priority would you give to this rule?

A
1000

B
1

C
65535

D
0

1
Kategori : EN - Planning and configuring a cloud solution 1

Your client wants to develop a new cost-effective web application that runs on a serverless platform using Cloud Function, Cloud Storage, Pub/Sub, and Cloud CDN. The expected data would be 20 GB. Which of the following databases would be the most suitable schemaless option to support the serverless functionality?

A
Cloud Firestore

B
Cloud Bigtable

C
BigQuery

D
Cloud Spanner

1
Kategori : EN - Planning and configuring a cloud solution 1

You are working for a genomics company in the US that is planning to conduct data analysis on around 10 TB of data. The company would require 20 vCPUs and 60 GB of RAM for the VM. You have been asked to figure out the cheapest option to conduct the analysis. Which of the following would you use?

A
Sustained discount

B
Committed use discount

C
Preemptible instances

D
Cloud Functions

1
Kategori : EN - Planning and configuring a cloud solution 1

You work for a financial company as a Cloud Engineer. Your manager asked you to find a solution to store audit log files for 3 years. Your company has hundreds of GCP projects. You need to implement a cost-effective approach for log file retention. What solution that you will give to the manager?

A
Create an export to the sink that saves logs from Cloud Audit to a coldline Cloud Storage bucket.

B
Create an export to the sink that saves logs from Cloud Audit to BigQuery.

C
Write a custom script that uses logging API to copy the logs from Cloud Logging to BigQuery.

D
Export logs to Cloud Pub/Sub and write a Cloud Dataflow pipeline to store logs to Cloud SQL.

1
Kategori : EN - Planning and configuring a cloud solution 1

You are building up an application for your client which has Web, API, and DB layers. The client has asked you to decouple the application so that each request is successfully acknowledged and processed by the application layer. Which service will you use for this need?

A
App Engine

B
Cloud Dataproc

C
Cloud Functions

D
Cloud Pub/Sub

1
Kategori : EN - Planning and configuring a cloud solution 1

You are working along with a team of developers who are building an accounting application for a startup. Until now, they were using VM disk to store logs but have now realized that this strategy is not scalable and want a different solution to store logs. Which service would you recommend to the team?

A
Activity Logs

B
Cloud Logging

C
Flow Logs

D
Google Kubernetes Engine

1
Kategori : EN - Planning and configuring a cloud solution 1

You have to build a functionality to manage user sessions in an online shopping cart for retail transactions. There is a need to ensure that users can lock down one or more documents until their transaction is complete. What would be the correct choice of database to handle the requirement?

A
Use BigQuery for streaming data from user sessions.

B
Use Cloud Firestore to handle user session management.

C
Use Cloud SQL and use sub-queries to hold the session.

D
Use Cloud Spanner to manage user sessions.

1
Kategori : EN - Planning and configuring a cloud solution 1

Your manager asked you to configure a solution for archiving data in a Cloud Storage bucket. These are the requirements given by the manager:

1. It must be cost-effective.

2. Data with multiple versions should be archived after 30 days.

3. Previous versions are accessed once a month for reporting.

4. This archived data is also occasionally updated at month-end.

Considering those requirements, what should you do?

A
Add a bucket lifecycle rule that archives data with newer versions after 30 days to Coldline Storage.

B
Add a bucket lifecycle rule that archives data with newer versions after 30 days to Nearline Storage.

C
Add a bucket lifecycle rule that archives data from regional storage after 30 days to Coldline Storage.

D
Add a bucket lifecycle rule that archives data from regional storage after 30 days to Nearline Storage.

1
Kategori : EN - Deploying and implementing a cloud solution 1

Your company is about to migrate a few of its servers initially from on-premise to Google Cloud and you have been asked to lead this task. All the instances have been migrated completely, but you are still left with creating health checks for all the instances. Which Google Cloud service will help you create health checks?

A
Prometheus

B
Grafana

C
Cloud Monitoring

D
Cloud Alerts

1
Kategori : EN - Deploying and implementing a cloud solution 1

You have been asked to automate the infrastructure deployment using the Google Deployment Manager service. Which format does the Google Cloud Deployment Manager template support?

A
JSON

B
TXT

C
YAML

D
Powershell

1
Kategori : EN - Deploying and implementing a cloud solution 1

You work for a retail company that has a busy online store. As you are approaching the new year, you find that your e-store is getting more and more traffic. You ensure that your web servers are behind a managed instance group. However, you notice that the web tier is frequently scaling, sometimes multiple times in an hour. You need to keep the instance group from scaling up and down so rapidly. Which of the following options would help you achieve this?

A
Change the autoscaling metric to use multiple metrics instead of just one metric.

B
Reduce the number of maximum instance counts.

C
Associate a health check with an instance group.

D
Increase the cooldown period.

1
Kategori : EN - Deploying and implementing a cloud solution 1

A bug has been identified within your Python application which is hosted using App Engine and you are about to roll out a new version of the application to resolve the bug, but do not want the traffic to automatically shift to a new version just to make sure the new version does not break anything. How would you achieve it?

A
Pass --no-active flag while deploying a new version.

B
Pass a custom version ID so that App Engine does not send traffic to the new version.

C
Pass --no-promote flag while deploying a new version.

D
Use --inactive-mode flag while deploying a new version of the app.

1
Kategori : EN - Deploying and implementing a cloud solution 1

You have an application server running on Compute Engine in the europe-west1-d zone. You need to ensure high availability and replicate the server to the europe-west2-c zone using the fewest steps possible. What should you do?

A
Create a snapshot from the disk. Create a disk from the snapshot in the europe-west2-c zone. Create a new VM with that disk.

B
Create a snapshot from the disk. Create a disk from the snapshot in the europe-west1-d zone and then move the disk to europe-west2-c. Create a new VM with that disk.

C
Use “gcloud” to copy the disk to the europe-west2-c zone. Create a new VM with that disk.

D
Use “gcloud compute instances move” with the parameter “--destination-zone europe-west2-c” to move the instance to the new zone.

0
Kategori : EN - Deploying and implementing a cloud solution 1

In your company, there are massive data services that are currently running Hadoop/Spark on-premises. The Cloud Architects start their work on a migration plan to Google Cloud. However, the big data team wants to use the existing workflows during the migration. The main focus is to continue working on their Hadoop cluster and Spark jobs with the scaling and data processing capacity of Google Cloud. Which tool would be the right option to choose?

A
Cloud Dataproc

B
Cloud Dataflow

C
Cloud Dataprep

D
Looker Studio

1
Kategori : EN - Deploying and implementing a cloud solution 1

An IoT (Internet of Things) application system needs to ingest and process the streaming sensor data received from multiple sources of connected devices. Choose the best set of tools to handle incoming data.

A
Use Cloud SQL database and run queries to process the data.

B
Use REST API exposed using App Engine and post data from endpoints.

C
Use Cloud Dataprep to cleanse the incoming data and run a Cloud Functions to process it.

D
Use Cloud Pub/Sub to receive data and process it via Cloud Dataflow pipelines.

1
Kategori : EN - Deploying and implementing a cloud solution 1

Your program manager wants you to set up a hybrid network between your Google Cloud and on-premise infrastructure that allows high bandwidth, low latency connection between both networks. As a Senior Cloud Engineer, which one of the following services will you select?

A
Cloud VPN

B
Cloud Router

C
Cloud Interconnect

D
Shared VPC

1
Kategori : EN - Deploying and implementing a cloud solution 1

You have been asked to create robust Virtual Private Network (VPN) connectivity between a new Virtual Private Cloud (VPC) and a remote site. Key requirements include dynamic routing, a shared address space of 10.19.0.1/22, and no overprovisioning of tunnels during a failover event. You want to follow Google-recommended practices to set up a high-availability Cloud VPN. What should you do?

A
Use a custom mode VPC network, configure static routes, and use active/passive routing.

B
Use a custom mode VPC network, use Cloud Router border gateway protocol (BGP) routes, and use active/passive routing.

C
Use an automatic mode VPC network, configure static routes, and use active/active routing.

D
Use an automatic mode VPC network, use Cloud Router border gateway protocol (BGP) routes, and configure policy-based routing.

1
Kategori : EN - Deploying and implementing a cloud solution 1

Your client is planning to deploy an application on App Engine and has a requirement to store 1 TB of data in a schemaless, a strongly consistent, ACID-compliant database solution. Which of the following would you consider for this?

A
Cloud Datastore

B
Cloud SQL

C
Cloud Storage

D
Cloud Bigtable

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

You are working as a System Administrator and have been asked to make sure that all images are patched up to date and developers are not allowed to use old images that are not up to date as per PCI compliance. How would you achieve this?

A
Drop a mail to all the developers regarding which image to use whenever you patch images.

B
Mark the image as deprecated to prevent users from using the old image.

C
Mark the image as obsolete to prevent users from using the old image.

D
None of the above.

0
Kategori : EN - Ensuring successful ops of a cloud solution 1

You need to select and configure compute resources for a set of batch processing jobs. These jobs take around 2 hours to complete and are run nightly. You want to minimize service costs. What should you do?

A
Select Google Kubernetes Engine. Use a three-node cluster with micro instance types.

B
Select Google Kubernetes Engine. Use a single-node cluster with a small instance type.

C
Select Compute Engine. Use preemptible VM instances of the appropriate standard machine type.

D
Select Compute Engine. Use VM instance types that support micro bursting.

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

You have a website hosted on a Compute Engine VM. Users can access the website using the domain name you provided. You do some maintenance work on the VM and stop the server and restart it. Now users cannot access the website. No other changes have occurred on the subnet. What might be the cause of the problem?

A
The restart caused a change in the DNS record.

B
You used an ephemeral instead of a static IP address.

C
You do not have enough addresses available on your subnet.

D
Your subnet has changed.

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

You have production and test workloads that you want to deploy on Compute Engine. Production VMs need to be in a different subnet than the test VMs. All the VMs must be able to reach each other over Internal IP without creating additional routes. You need to set up VPC and the 2 subnets. Which configuration meets these requirements?

A
Create a single custom VPC with 2 subnets. Create each subnet in a different region and with a different CIDR range.

B
Create a single custom VPC with 2 subnets. Create each subnet in the same region and with the same CIDR range.

C
Create 2 custom VPCs, each with a single subnet. Create each subnet in a different region and with a different CIDR range.

D
Create 2 custom VPCs, each with a single subnet. Create each subnet in the same region and with the same CIDR range.

0
Kategori : EN - Ensuring successful ops of a cloud solution 1

Your projects incurred more costs than you expected last month. Your research reveals that a development Google Kubernetes Engine container emitted a huge number of logs, which resulted in higher costs. You want to disable the logs quickly using the minimum number of steps. What should you do?

A
1. Go to the Logs ingestion window in Stackdriver Logging.

2. Disable the log source for the Google Kubernetes Engine Cluster Operations resource.

B
1. Go to the Google Kubernetes Engine console and delete existing clusters.

2. Recreate a new cluster. 

3. Clear the option to enable legacy Stackdriver Logging.

C
1. Go to the Logs ingestion window in Stackdriver Logging.

2. Disable the log source for the Google Kubernetes Engine container resource.

D
1. Go to the Google Kubernetes Engine console and delete existing clusters. 

2. Recreate a new cluster. 

3. Clear the option to enable legacy Stackdriver Monitoring.

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

You are working on a project whose development phase has been completed and the manager has asked you to create a new project for the UAT environment which should be a clone of the development environment. The development environment consists of 5 VMs which need to be replicated in the UAT environment. How can you achieve this?

A
Launch 5 VMs from scratch and install all the libraries one by one.

B
Select an instance, click on Actions, and use migrate option to launch VM in another project.

C
Create a custom image of each instance in the development environment. While launching VMs in the UAT environment, under boot disk, select Custom images, select your project, and choose the relevant image.

D
None of the above

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

Your team has a VM instance that is currently launched with 2 vCPUs and 4 GB of memory to host e-learning applications. After several hours, the VM instance is running out of memory. You want to upgrade the VM instance to have 8 GB of memory. What should you do?

A
Rely on live migration to move the workload to a machine with more memory.

B
Stop the VM, change the machine type to n1-standard-8, and start the VM.

C
Stop the VM, increase the memory to 8 GB, and start the VM.

D
Use gcloud to add metadata to the VM. Set the key to required-memory-size and the value to 8 GB.

0
Kategori : EN - Ensuring successful ops of a cloud solution 1

You recently deployed a new version of an application to App Engine and then discovered a bug in the release. You need to immediately revert to the prior version of the application. What should you do?

A
On the App Engine Versions page of the Cloud Console, route 100% of the traffic to the previous version.

B
On the App Engine page of the Cloud Console, select the application that needs to be reverted and click Revert.

C
Run gcloud app restore.

D
Deploy the original version as a separate application. Then go to App Engine settings and split traffic between applications so that the original version serves 100% of the requests.

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

Your company is operating as an IT contractor for a government project. Due to new data regulations, instructions have been provided for your team to adhere to the compliance terms, audit, and hold it with retention for 5 years. The infrastructure for the project run primarily on Compute Engine VM instances and persistent disk data attached to them. The backup will be accessed rarely during auditing reviews held once a year.

Which of the following would be the ideal choice?

A
Use Machine Images to store all the configuration, metadata, permissions, and data from one or more disks required to create a virtual machine (VM) instance.

B
Use a Regional persistent disk to Replicate data synchronously across two zones in the same region.

C
Use Disk Clones to create live, attachable, fully provisioned disks with data from a source disk.

D
Use Archive snapshots for Long retention backup and geo-redundancy.

1
Kategori : EN - Ensuring successful ops of a cloud solution 1

You need to grant access for three users so that they can view and edit table data on a Cloud Spanner instance. What should you do?

A
Run gcloud iam roles describe roles/spanner.viewer - -project my-project. Add the users to the role.

B
Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to the role.

C
Run gcloud iam roles describe roles/spanner.databaseUser. Add the users to a new group. Add the group to the role.

D
Run gcloud iam roles describe roles/spanner.viewer - -project my-project. Add the users to a new group. Add the group to the role.

0
Kategori : EN - Configuring access and security 1

In your Company, two teams are working on their respective GCP projects with similar cloud resources. Due to time constraints and minimizing the work of creating separate VPC networks, they have a requirement of using the same subnet. Which of the following would enable both teams while maintain centralized control over network resources like subnets, routes, and firewalls?

A
Create a Shared VPC and attach service projects to it to use the same subnet.

B
Create a Shared VPC and designate a project as a host project and attach the other service projects to it to use the same subnet.

C
Create a custom-mode VPC and use the same subnet.

D
Create an auto-mode VPC and use the same subnet for each region.

1
Kategori : EN - Configuring access and security 1

Your company has purchased a threat detection service from a third party and has asked you to upload all network logs to the application. Which of the following service will meet your requirements?

A
Flow Logs

B
Activity Logs

C
Network Logs

D
System Logs

1
Kategori : EN - Configuring access and security 1

Your client has one GCP project called proj-sa where you manage all your service accounts. You want to be able to use a service account from this project to take snapshots of VMs running in another project called proj-vm. What should you do?

A
Download the private key from the service account, and add it to each VMs custom metadata.

B
Download the private key from the service account, and add the private key to each VM's SSH keys.

C
Grant the service account the IAM role of Compute Storage Admin in the project called proj-vm.

D
When creating the VMs, set the service account's API scope for Compute Engine to read/write.

1
Kategori : EN - Configuring access and security 1

Your company has deployed an application using an App Engine standard environment. You have been asked to update the cron schedules and default cookie expiration time. Which of the following predefined roles has access to update default cookie expiration but no access to update cron schedules?

A
App Engine Service Admin

B
App Engine Admin

C
App Engine Deployer

D
App Engine Code Viewer

1
Kategori : EN - Configuring access and security 1

You are appointed as a head of infrastructure security and the first thing you are asked is to create a few IAM users following best security practices. How would you ensure that these users are only able to launch a new instance and list them?

A
Create Compute Editor role and attach it to the users.

B
Attach Project Editor role to users.

C
Create a custom role with specific permissions and attach it to users.

D
Create a service account with the required permissions and attach it to users.

1
Kategori : EN - Configuring access and security 1

The development team wants to deploy an application on Cloud Run that processes messages from a Cloud Pub/Sub topic. You've been designated to give them a solution for the possible steps. They want to follow Google-recommended practices. What solution you will provide to them?

A
1. Create a Cloud Functions that use a Cloud Pub/Sub trigger on that topic. 

2. Call your application on Cloud Run from the Cloud Functions for every message.

B
1. Create a service account. 

2. Give the Cloud Run Invoker role to that service account for your Cloud Run application. 

3. Create a Cloud Pub/Sub subscription that uses that service account and uses your Cloud Run application as the push endpoint.

C
1. Grant the Pub/Sub Subscriber role to the service account used by Cloud Run. 

2. Create a Cloud Pub/Sub subscription for that topic. 

3. Make your application pull messages from that subscription.

D
1. Deploy your application on Cloud Run on GKE with the connectivity set to Internal. 

2. Create a Cloud Pub/Sub subscription for that topic. 

3. In the same Google Kubernetes Engine cluster as your application, deploy a container that takes the messages and sends them to your application.

1
Kategori : EN - Configuring access and security 1

Your company has a Google Cloud Platform project that uses BigQuery for data warehousing. Your data science team changes frequently and has few members. You need to allow members of this team to perform queries. You want to follow Google-recommended practices. What should you do?

A
1. Create a dedicated Google group in Cloud Identity. 

2. Add each data scientist's user account to the group. 

3. Assign the BigQuery dataViewer user role to the group.

B
1. Create a dedicated Google group in Cloud Identity.

2. Add each data scientist's user account to the group. 

3. Assign the BigQuery jobUser role to the group.

C
1. Create an IAM entry for each data scientist's user account. 

2. Assign the BigQuery dataViewer user role to the group.

D
1. Create an IAM entry for each data scientist's user account. 

2. Assign the BigQuery jobUser role to the group.

0
Kategori : EN - Configuring access and security 1

Your colleague was assigned a new DevOps project in Google Cloud Platform and he needs deploymentmanager.deployments.* permission to make use of Deployment Manager service. Which of the following roles would you create for him?

A
Deployment Manager Editor

B
Deployment Manager Custom

C
Deployment Manager Type Viewer

D
Deployment Manager Viewer

0
Kategori : EN - Configuring access and security 1

One of your team members had accidentally included a service account private JSON key while pushing code to GitHub. What steps should you immediately perform?

A
Delete the JSON file from GitHub.

B
Delete the project and all its resources.

C
Delete the JSON file from GitHub, remove the key from Google Cloud IAM and generate a new key for use.

D
None of the above

1
Kategori : EN - Configuring access and security 1

Someone from a different team has approached you that he is working on a web application hosted on Compute Engine VM instance which needs to view access to Cloud Storage service. Which of the following is the best approach using the fewest possible steps?

A
Create a custom service account with the Cloud Storage Viewer role, and attach it to the VM instance.

B
Create a custom service account with Cloud Storage Viewer role, create a JSON key pair, and provide it to him.

C
VM Instances by default have read access to Cloud Storage service, so nothing needs to be done.

D
Create an IAM user for him with Cloud Storage, create a JSON key pair, and provide it to him.
