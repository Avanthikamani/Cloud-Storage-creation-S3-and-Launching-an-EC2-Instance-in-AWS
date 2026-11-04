# Cloud-Storage-creation-S3-and-Launching-an-EC2-Instance-in-AWS
Ex.2 Cloud storage creation (S3) and launching an (Ec2) instance in AWS
Aim:
To create a Simple Storage Service (S3) in AWS and to launch an EC2 instance in AWS. 
Procedure
a)	Steps to Create a first S3 Bucket:
Step 1: Sign in to the AWS Management Console
Go to https://console.aws.amazon.com/s3.
Step 2: Open the S3 Service
In the console, type S3 in the search bar and select S3 to open the service dashboard.
Step 3: Create Bucket
Click the Create bucket button.
Step 4: Configure Bucket Settings
•	Bucket name: Choose a globally unique name.
•	AWS Region: Select the region where you want to store your data.
Step 5: Object Ownership
Choose between:
	ACLs disabled (recommended) – Bucket owner has full control.
	ACLs enabled – Control access via access control lists.
Step 6: Block Public Access Settings
By default, all public access is blocked. Leave it as-is unless you need public access.
Step 7: Bucket Versioning (optional)
Choose whether to enable versioning for objects in the bucket.
Step 8: Encryption (optional)
Select encryption options (SSE-S3, SSE-KMS, or none).
Step 9: Advanced Settings (optional)
Add tags, configure logging, etc.
Step 10: Create the Bucket
Click Create bucket at the bottom of the page.
b)	i. Steps to launch an EC2 Instance
1.	Go to the EC2 Dashboard in AWS Console.
2.	Click on “Launch Instance”.
3.	Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux).
4.	Select an instance type (e.g., t2.micro for Free Tier).

5.	Create or choose a key pair for SSH access.
6.	Configure network settings (use default VPC/subnet).
7.	Configure storage (default root volume is fine).
8.	Review the settings and click “Launch Instance”.
9.	Wait for the instance to enter the running state.

c)	Step 3: Connect to Your Instance
•	Linux: Use SSH command with your .pem key.
•	Windows: Use RDP with decrypted admin password.

d)	Steps to Clean Up (Terminate the Instance)
1.	Go to EC2 Instances.
2.	Select your instance → Instance State → Terminate.


Snap Shots:

<img width="1913" height="1022" alt="Screenshot 2026-11-01 090710" src="https://github.com/user-attachments/assets/953f8a37-20fb-4770-a5d1-0fa618be2553" />
<img width="1913" height="1035" alt="Screenshot 2026-11-01 091004" src="https://github.com/user-attachments/assets/6acfeb47-2c11-40d6-a5bf-b47db9d084c9" />
<img width="1917" height="1032" alt="Screenshot 2026-11-01 091022" src="https://github.com/user-attachments/assets/908fd246-627d-4fd7-95c3-9d5f8794682b" />
<img width="1917" height="1016" alt="Screenshot 2026-11-01 091524" src="https://github.com/user-attachments/assets/23d0b2eb-d2c6-4736-ae9c-035887077566" />
<img width="1917" height="1022" alt="Screenshot 2026-11-01 094501" src="https://github.com/user-attachments/assets/dd5a04c3-b713-4c37-adcc-87daa0d515b1" />
<img width="1917" height="278" alt="Screenshot 2026-11-01 095954" src="https://github.com/user-attachments/assets/33da1c90-91f8-4f25-b1c7-a1ebf62c90c7" />









Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
