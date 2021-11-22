## IAM = Identity and Access Management, Global Service
Permissions: Users can be assigned JSON Documents to allow users some services in AWS. In AWS we do not allow all the services to all the users. You apply Least Privilege principle.

## In IAM- 
	1. Created a new user which will have admin privileges so that wont need to use the root account coz its dangerous from security perspective.
	2. Created a new group called Admin and assigned permissions via assigning the policies. eg. Policy Name: AdministratorAccess
	3. Skipped adding users
	4. Add tags (tags are just information that can help you track, organize or control access for users.) Added tag- Departement -> Engineering
	5. Proceed to review then select Create User. Download csv or can send email with credentials. 
Review the group. It contains one user Nirali with Admin access permission.

In dashboard -> Created alias for the AWS account
Now login as the IAM user. 

## IAM policies structure:
	1. Consists of:
		a. Version: Policy language version, "2012-10-I7"
		b. Id: identifier for the policy (optional)
		c. Statement: one or more individual statements
	2. Statement consists of:
		a. Sid: an identifier for the statement (optional) 
		b. Effect: whether the statement allows or denies access (Allow, Deny)
		c. Principal: account/user/role to which the policy is applied to
		d. Action: list of actions this policy allows or denies
		e. Resource: list of resources to which the actions will be applied to
		f. Condition (optional): Conditions for which the resources are applied to.

## IAM policies hands-on
	1. Deleted the user from IAM account
	2. Added the permission from the root account
  3. Juggled between the IAM account and the root account to perform actions like adding user, creating groups, adding/deleting the permissions/policies ![image](https://user-
