### EOM2-Terraform-Exercise


## Exercise
![Screenshot 2024-09-26 172908](https://github.com/user-attachments/assets/de0eea82-ebe7-447f-9092-07c7841a0bd5)
1.	Create AWS VPC and its networking components similar to AWS Cloud > Test Yourself > (1) using Terraform Resources. Ensure that the output is the same as that created via the cloud console.

2.	Create AWS VPC and its networking components similar to AWS Cloud > Test Yourself > (1) using Terraform Module. Ensure that the output is the same as that created via the cloud console.

3.	Create an EC2 using Terraform Resources and place it inside the public subnet of your previously created VPC. Ensure that you install Apache Web Server via User Data/ Bootstrap script. 

4.	Further Test: Create an RDS with MySQL installed with Terraform, and ensure it works as expected as AWS Cloud > Test Yourself > (4). Test whether you can connect to the RDS via MySQL Workbench if you would like to.

5.	Further Test: Create a Lambda Function that prints a simple “Hello World” in Python using Terraform. Refer to AWS Cloud > Test Yourself > (9) as well as LINK on how to achieve this.

6.	Utilize dev.tfvars, uat.tfvars, and prod.tfvars on the same Terraform codes to allow you to create multiple resources for different environments using Terraform workspaces. Run the code from this LINK locally (without Github Actions first)

