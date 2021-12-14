## AWS CloudShell
AWS CloudShell is a browser-based shell that makes it easy to securely manage, explore, and interact with your AWS resources. ... With CloudShell, you can quickly run scripts with the AWS Command Line Interface (AWS CLI), experiment with AWS service APIs using the AWS SDKs, or use a range of other tools to be productive.

## IAM Roles: 
Are roles created for certain AWS services to perform actions on your behalf.

## IAM Roles Handson:
In IAM account. Roles -> Create a Role -> With IAMReadOnlyAccess -> Gave name	DemoRoleForEC2

## IAM Security Tools:
	1. IAM Credentials Report (account-level):
		a. A report that lists all your account's users and the status of their various credentials
	2. IAM Access Advisor (user-level):
		a. Access advisor shows the service permissions granted to a user and when those services were last accessed. 
		b. You can use this information to revise your policies.

IAM Security Tools Hands-on:

## Shared Responsibility Model for IAM:
AWS	You
Infrastructure (global network security)	Users, Groups, Roles, Policies management and monitoring
Configuration and vulnerability analysis	Enable MFA on all accounts
Compliance validation	Rotate your keys often
	Use IAM tools to apply appropriate permissions. Analyze access patterns and review permissions

## IAM Summary:
	1. Users: mapped to a physical user; has a password for AWS Console
	2. Groups: contains users only
	3. Policies: JSON Document that outlines permissions for users or groups
	4. Roles: for EC2 instances or AWS services
	5. Security: MFA + Password Policy
	6. AWS CLI: manage your AWS services using the command-line
	7. AWS SDK: manage your AWS services using a programming language
	8. Access Keys: access AWS using the CLI or SDK
	9. Audit: IAM Credentials Reports and IAM Access Advisor
![image](https://user-images.githubusercontent.com/58590628/145946572-b09abe13-5db7-4be1-97ba-c4ff8ccb1c8d.png)
