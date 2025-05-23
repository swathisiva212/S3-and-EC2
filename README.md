 ## Aim:
 To Create S3 bucket and EC2 Instances for Linux and Windows.
 ## S3 Bucket:
 An S3 bucket is a cloud storage container provided by Amazon Web Services (AWS) throughits Simple Storage Service (S3). It is used to store and organize data, such as files, images,backups, and more, in a scalable, secure, and durable way.
## EC2 Instance:
  EC2 Instance:
 An Amazon EC2 instance is a virtual server in Amazon's Elastic Compute Cloud (EC2)—ascalable compute platform designed for running applications on the Amazon Web Services(AWS) cloud.EC2 offers a wide range of instance types and sizes, each providing differentconfigurations of CPU (central processing unit),Memory,Storag,,Networking resources.Theseconfigurations allow users to choose instances that best match their specific applicationrequirements and workloads—whether for general-purpose use, compute-intensive tasks,memory-heavy processing, or high-speed networking. 

  ## Procedure:
 Step 1:
● Log in to AWS Console

 Step 2:
● Create an S3 Bucket

● Navigate to the S3 service.

● Click on Create bucket.

● Enter a Bucket name and select a Region.

● Configure Bucket settings as required (e.g., versioning, public access).

● Click on Create bucket to finalize.

 Step 3:
● Create an EC2 Instance (Linux)

● Go to the EC2 service.

● Click on Launch Instance.

● Select an Amazon Machine Image (AMI) for Linux (Amazon Linux 2).

● Choose an Instance Type (e.g., t2.micro for free tier).

● Configure Instance Details, Storage, and Security Group. 

● Review and click Launch with a key pair (or create one if needed).

 Step 4:
● Create an EC2 Instance (Windows)

● Return to the EC2 service and click Launch Instance.

● Select a Windows AMI (e.g., Windows Server 2019).

● Choose the Instance Type.

● Configure Instance Details, Storage, and Security Group.

● Review and launch with a key pair (for future login).

 Step 5:
● Verify and Connect to Instances.
● Verify the status of both instances in the EC2 dashboard.
● Connect to the Linux instance using SSH.
● Connect to the Windows instance using RDP. 
## output:
![image](https://github.com/user-attachments/assets/98375662-911e-45c9-b73e-4864e5b2cd4a)


## Result:
 Successfully created an S3 bucket and EC2 instances for both Linux and Windows,
demonstrating cloud resource management on AWS 
