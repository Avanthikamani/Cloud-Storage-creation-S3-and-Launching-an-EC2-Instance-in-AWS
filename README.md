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

<img width="1920" height="1080" alt="Screenshot (175)" src="https://github.com/user-attachments/assets/ae77cad7-487d-4d8c-891e-e20080347590" />

<img width="1920" height="1080" alt="Screenshot (176)" src="https://github.com/user-attachments/assets/697ee171-28b3-4c6a-a585-fe7d62657acd" />

<img width="1920" height="1080" alt="Screenshot (177)" src="https://github.com/user-attachments/assets/004cac9f-bd36-42bd-a766-66cebe40323d" />

<img width="1920" height="1080" alt="Screenshot (178)" src="https://github.com/user-attachments/assets/21a2ef80-8faa-4976-8613-6dfcf9d80b10" />

<img width="1920" height="1080" alt="Screenshot (179)" src="https://github.com/user-attachments/assets/650ed17f-01e7-4bcc-911e-19c7313f7786" />

<img width="1920" height="1080" alt="Screenshot (180)" src="https://github.com/user-attachments/assets/f291bc18-ac33-4e9f-8cea-11adf5da6358" />

<img width="1920" height="1080" alt="Screenshot (181)" src="https://github.com/user-attachments/assets/f33c95a7-f41e-4476-a270-15657f4740f2" />

<img width="1920" height="1080" alt="Screenshot (183)" src="https://github.com/user-attachments/assets/6387e2f0-d6ce-47a9-b15b-a094cbe12752" />

<img width="1920" height="1080" alt="Screenshot (184)" src="https://github.com/user-attachments/assets/c9478aba-2e91-4346-a5de-03eecb15b83e" />

<img width="1920" height="1080" alt="Screenshot (186)" src="https://github.com/user-attachments/assets/136066e9-b412-45e3-8b54-b19b134e872d" />

<img width="1920" height="1080" alt="Screenshot (187)" src="https://github.com/user-attachments/assets/d7d00a9f-4065-4117-92a5-0b25cc83da70" />

<img width="1920" height="1080" alt="Screenshot (188)" src="https://github.com/user-attachments/assets/5027ac4c-d386-4cce-aed9-b994c72b1b7c" />

<img width="1920" height="1080" alt="Screenshot (190)" src="https://github.com/user-attachments/assets/bdb18258-f1e2-48f6-a9be-d1d8aa1a65d5" />

<img width="1920" height="1080" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/d7d9f1f4-1ee3-4463-bafb-0d98bf8db34b" />

<img width="1920" height="1080" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/3a459d00-b88e-4d4b-b77e-30df07a6ad34" />

<img width="1920" height="1080" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/74f3651b-3826-49c1-9498-0975b0261eb3" />

<img width="1920" height="1080" alt="Screenshot (197)" src="https://github.com/user-attachments/assets/513a66f0-a423-437f-9aa0-5edb9a011c3b" />




Result:
Thus, a Simple Storage Service (S3) and EC2 (Elastic Compute Cloud) - instance has been successfully created and launched in AWS
 
