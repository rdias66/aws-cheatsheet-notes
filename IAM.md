### IAM 

- No root usage aside from first setup.
- Create Users into Groups with asigned permissions. 
- Configure User's accesses with MFA, access will happen through those(no root account login, user name and corresponding password).
- For in-service usage of external resources(such as cleaner-ecr from within EC2), use Roles with necessary permissions assigned to the service in question.
> Current usage of admin user within EC2's for the cleaner script is wrong and overkill, possibly raises security issues.
