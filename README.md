I installed and configured the AWS CLI on a Red Hat Linux instance because this instance type does not have the AWS CLI pre-installed. Some instance types, such as Amazon Linux, do come pre-installed with the AWS CLI AWS-CLI.
I established a Secure Shell (SSH) connection to the instance. I configured the installation with an access key that can connect to an AWS account. Finally, I practiced using the AWS CLI to interact with AWS Identity and Access Management (IAM)
I log in to an existing EC2 instance with the help of Putty.

Objectives:
Install and configure the AWS CLI.
Connect the AWS CLI to an AWS account.
Access IAM by using the AWS CLI.

Install the AWS CLI on a Red Hat Linux instance:
To save the downloaded file in the current directory, execute the following curl command, using the -o option:            curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
To extract the installer, use the following unzip command and include the -u option:                                      unzip -u awscliv2.zip
To extract the installer, use the following unzip command and include the -u option:                                      sudo ./aws/install
To verify the installation, execute the following command:                                                                aws --version
I will get a following output:                                                                                            aws-cli/2.15.24 Python/3.11.6 Linux/4.14.336-256.559.amzn2.x86_64 exe/x86_64.amzn.2 prompt/off
To ensure that the AWS CLI is functioning correctly, execute the following command:                                       aws help
At the : prompt, enter q to exit

Observe IAM configuration details in the AWS Management Console:
I observed the IAM configuration details for the EC2 instance in the AWS Management Console
