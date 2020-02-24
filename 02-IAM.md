### IAM
[Security Best Practises](https://d0.awsstatic.com/whitepapers/Security/AWS_Security_Best_Practices.pdf)

IAM allows you to manage users and their level of accesses to the AWS Console:
 - Centralized control of your AWS account
 - Shared Access to your AWS account
 - Granular Permissions
 - Identity Federation 
 - Multifactor Authentication
 - Provides temporary access for users/devices and services, as necessary
 - Allows you to set up your own password rotatoin policy
 - Integrates with many different AWS services
 - Supports PCI DSS Compliance
 
 
 #### Critical Terms
 - Users
 - Groups, a collection of users
 - Roles, assignable to AWS resources
 - Policies, a collection of permissions
 
 
 #### Summary
- IAM consists of: Users Groups, Roles, Policy Documents
- IAM is universal. It does not apply to regions at this time.
- The root account is the account created when first setup your AWS account. It has complete Admin access.
- New Users have no permissions when first created.
- New Users are assigned Access Key ID & Secret Access Keys when first created. 
  - These are not the same as a password, and you canot use the Access key ID & Secret Access Key to Login in to the AWS Management Console.
  - You can use this to access AWS via the APIs and Command Line, however.
  - You only get to view Access key ID & Secret Access Key once. If you lose them, you have to regenerate them. 
- Always setup Multifactor Authentication (MFA) on your root account.
- You can create and customize your own password rotation policies.
