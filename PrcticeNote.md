# Overview
### AWS CodeCommit is a highly scalable, managed source control service that hosts private Git repositories. CodeCommit stores your data in Amazon S3 and Amazon DynamoDB giving your repositories high scalability, availability, and durability. You simply create a repository to store your code. There is no hardware to provision and scale or software to install, configure, and operate.
This hands-on lab gives you practice with AWS CodeCommit, part of AWS Developer Tools. In this lab, you first create a code repository in AWS CodeCommit. Then you create a local repository on a Linux instance running in EC2. After you create the local repo, you make some changes to it. Then you synchronize (commit) your changes to the AWS CodeCommit repository.

### Topics covered
#### This lab demonstrates how to:
    • Create a code repository using AWS CodeCommit via the Amazon Management Console 
    • Create a local code repository on the Linux instance using git 
    • Synchronize a local repository with an AWS CodeCommit repository 

### Task 1: Create an AWS CodeCommit repository
  Create a CodeCommit repository named My Repo.
  ![Screenshot from 2023-10-15 19-35-57](https://github.com/PromiseNwachukwu/Working-with-AWS-CodeCommit/assets/109115304/8ea095c5-9cbd-4016-a0b5-479908978617)

### Task 2: Connect to the Amazon EC2 instance
  Copy the Ec2InstanceSessionUrl value from the list to the left of these instructions, and then paste it into a new web browser tab.




![Screenshot from 2023-10-15 19-10-08](https://github.com/PromiseNwachukwu/Working-with-AWS-CodeCommit/assets/109115304/4fb6b477-c2c5-4025-854d-e6cfdb94e329)


![Screenshot from 2023-10-15 19-10-18](https://github.com/PromiseNwachukwu/Working-with-AWS-CodeCommit/assets/109115304/bac5381b-3976-4742-9dd9-d7398599c8b9)


![Screenshot from 2023-10-15 19-10-32](https://github.com/PromiseNwachukwu/Working-with-AWS-CodeCommit/assets/109115304/87738d7c-bdb4-4576-aa07-1f7458dd8844)
