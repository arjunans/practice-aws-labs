1. How to create a user in aws and assign administrator rights
	- Create an group in IAM as "aws-administrators"
	- Assign a policy "AdministratorAccess" & "Billing"
	- Create an user in IAM as "admin" and assign into "aws-administrators" group.
	- Assign MFA to the user for additional security.
	**Note:** don't user root user account to do day-to-day-activities.

2. How to create a simple VPC (Public subnets, Private subnets, Internet gateway, NAT gateway, Route tables)
   - VPC CIDR range: 10.0.0.0/26 (2 public subnets, 2 private subnets)

3. How to launch EC2 instance (windows) and configure IIS and try to access website using public IP address
   - Create t3 micro instance with windows 2022 base image and configure IIS

4. How to host static website in s3 bucket
   - Host a static website
  
   


 
 
 
 
