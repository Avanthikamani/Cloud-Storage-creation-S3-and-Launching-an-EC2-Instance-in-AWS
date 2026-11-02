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

 <img width="1920" height="1080" alt="Screenshot (167)" src="https://github.com/user-attachments/assets/6c444667-2b21-4004-a0cc-ac4e6a52dc1d" />

<img width="1920" height="1080" alt="Screenshot (168)" src="https://github.com/user-attachments/assets/a739086b-8273-481b-8847-d90c175a7c88" />

<img width="1920" height="1080" alt="Screenshot (169)" src="https://github.com/user-attachments/assets/bae9a873-0cba-42bc-9749-177f592c81eb" />

<img width="1920" height="1080" alt="Screenshot (170)" src="https://github.com/user-attachments/assets/c03514c5-8afd-41f4-8d88-76b82a485f0b" />

<img width="1920" height="1080" alt="Screenshot (171)" src="https://github.com/user-attachments/assets/77af8096-8b4e-4778-88a6-95a82f656dc3" />

<img width="1920" height="1080" alt="Screenshot (172)" src="https://github.com/user-attachments/assets/66aff768-96fd-40b7-ac58-e2e44e4f3f74" />

<img width="1920" height="1080" alt="Screenshot (173)" src="https://github.com/user-attachments/assets/fa3afe0f-6e21-40b1-a4e7-01c6fc23318d" />

<img width="1920" height="1080" alt="Screenshot (175)" src="https://github.com/user-attachments/assets/091b0dcd-4039-4924-a4c1-4bc57c5c9205" />

<img width="1920" height="1080" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/34ac5c09-1747-4d65-bb05-783fcddfa7b2" />

<img width="1920" height="1080" alt="Screenshot (177)" src="https://github.com/user-attachments/assets/a3ebcf42-11c2-4a36-844f-abc26031079b" />

<img width="1920" height="1080" alt="Screenshot (174)" src="https://github.com/user-attachments/assets/d702fe58-8b9b-421c-9347-caa70651dc76" />



















Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
