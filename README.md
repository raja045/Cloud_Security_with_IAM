# CLOUD_SECURITY_WITH_IAM
## OVERVIEW:
This project demonstrates the implementation and management of AWS Identity and Access Management (IAM) using two AWS instances: one for development and one for production. The goal is to showcase how to set up IAM roles, policies, and user management in a secure and scalable manner.

## AWS SERVICES USED:

- **AWS IAM:** For managing users, roles, and permissions.
- **AWS EC2:** To provision and manage development and production instances.


## FOLLOW THE STEPS BELOW
### STEP 1: CREATE TWO EC2 INSTANCES WITH TAGS 
**1.1 Launch EC2 Instances:** Provision two EC2 instances—one for development and one for production. Ensure they are appropriately configured for their respective environments. **1.2 Verify Tags:** Add and verify tags to identify and manage the instances easily.

![Greenshot 2024-08-21 09 48 35](https://github.com/user-attachments/assets/4dce5060-74a5-4f5b-b0ca-5f7d049b2cd0)


### STEP 2: CREATE AN IAM POLICY
Define and create an IAM policy that specifies the permissions required for your IAM roles and users. This policy will dictate what actions can be performed on the AWS resources.

![policy](https://github.com/user-attachments/assets/800e39f6-8b50-4a6b-aea9-8de1a687e8df)


### STEP 3: CREATE AN AWS ALIAS ACCOUNT
Set up an AWS alias account to simplify the management and identification of your AWS resources. This step involves configuring a custom alias for your AWS account.

![Alias](https://github.com/user-attachments/assets/e234c85e-26b9-4c21-8215-d29f0cd35f51)


### STEP 4: CREATE IAM USERS AND USER GROUPS 
**4.1 Create IAM User Groups:** Organize users into groups with specific permissions and roles. This helps in managing permissions more efficiently. **4.2 Create IAM Users:** Add users to your IAM system and assign them to the previously created groups. Ensure each user has appropriate permissions as per their role.

![Usergroup](https://github.com/user-attachments/assets/f91cf8de-4cc2-4528-9d03-9e04000d3650)


### STEP 5: LOGGING IN AS ‘IAM’ USER
Test logging into the AWS Management Console as one of the IAM users to verify that the setup is working as expected and that the permissions are correctly applied.

![user3](https://github.com/user-attachments/assets/2d36a989-40d4-456b-b88a-a42483b28435)


### STEP 6: TEST YOUR USER ACCESS
Conduct tests to ensure that IAM users have the appropriate level of access to the resources. Verify that they can perform the actions specified in their policies.

![test](https://github.com/user-attachments/assets/1a803534-bf75-4229-963e-fcd7263680e1)


## CHALLENGES FACED:
**AWS Free Tier Limited Resources:** The AWS Free Tier has limitations on the resources available, such as instance types and storage capacity. This constraint required careful planning and optimization to ensure the project could be completed within the free tier limits.

## VISIT THE BLOG 
For an in-depth look at cloud security with AWS IAM, including practical tips and detailed explanations, explore the Medium blog series:
- [Cloud Security with AWS IAM - Part 1](https://medium.com/@nakamotosecurity/cloud-security-with-aws-iam-part-1-4dbd2241b0ea)
- [Cloud Security with AWS IAM - Part 2](https://medium.com/@nakamotosecurity/cloud-security-with-aws-iam-part-2-06f635142a44)

## CONCLUSION:
“In this project, I successfully implemented AWS Identity and Access Management (IAM) to enhance security and streamline operations across development and production environments. By configuring precise user roles, and policies, I ensured robust access management and compliance with industry best practices. The project reinforced my skills in cloud security, and efficient resource management, preparing me to handle complex cloud infrastructure challenges.”
