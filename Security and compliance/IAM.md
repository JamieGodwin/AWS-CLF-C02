### IAM = Identity Access Management 
### Root users: Created by defaut, shouldn't be used or shared
### Users are people within the organisation that can be grouped 
- Groups can only contain users, not other groups.
- Users don't need to belong to a group at all, or could belong to multiple.

## IAM permissions
- Users can be JSON documents called policies.
- This essentially says what permissions the user will have.
- You apply the least priveledge principle, meaning you only give perission for what is needed. 

## IAM policies
- IAM Policies are rules you set in AWS to control who (like users and groups) can do what
- They are written in JSON format
- Action
    - Effect: Says if the rule allows or blocks access.
    - Action: Describes what actions (like read, write) are allowed or blocked.
    - Resource: Specifies which AWS resources (like a specific server or database) the rule applies to.
- You can use rules set by AWS, or make your own.

### Passwords
- You can decide on the password length, characters and such.
- Whether the user can reset their own passowrd
- Force a password reset after a certian amount of time
- Prevent re-use of the same password

### MFA
- You can set up MFA (multi factor authentication)
- This allows for better security. 
- you can have either a digital or physical MFA.

### Accessing your account
- There are three ways to access your AWS account:
    - Management console (password+mfa)
    - Command line interface/CLI (protected by access keys)
    - Software developer kit/SDK (protected by access keys)

- The keys are generated through the console
    - Users manage their own keys
    - They consist of a username (access key) and password (secret access key)

- The CLI allows you to access AWS through the terminal
    - Scripts can be used to control AWS
    - It's open source

- AWS SDK is a set of tools for developers to create applications that interact with AWS services. 
    - Provides easy to use API's
    - Embedded within the application

## Cloud shell
- It's like a command-line tool that you can use directly in your web browser to manage AWS stuff.
- You don't have to install anything on your computer to use it.
- You can type commands to do things like start a server or check your AWS services, right from the browser.

## IAM roles for services
- Some AWS services need to perform actions on your behalf
- They are permissions we give to AWS to do things for us

## IAM security tools
### Credentials report
- An account that lists the current users and their credentials

### Access advisor (user-level)
- Shows the service permissions granted to a user and when they were last accessed

## IAM best practices
- Only use the root account for setup
- One physical user = one AWS account
- Create a strog password
- Assign policies to groups, and then users to groups
- Audit your account permissions

