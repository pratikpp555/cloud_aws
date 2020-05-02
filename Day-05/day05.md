# AWS CLI
* AWS CLI stand for **AWS Command Line Interface**
* It is  an tool that enables you to interact with AWS services using commands in your command-line.
* we can update,delete create any resource uisng aws cli
* we use secret key and access key to access aws from outside while we use **IamRole** in the aws but we can use secret key and access key
in aws


#### To configure aws cli we edit ***credentials file***  from **.aws** and copy acccount details in it.


___
# RDS VS EC2
* Ec2 managed by aws but if you install any application within ec2 managed by developer
* Aws gives only mysql server and it is fully managed by aws 

___
# S3
* In bucket everything is an ***Object*** 
* Objects are immutable. to update we need to delete that file and upload again
___
# Lambda function
### Severless
* You dont own server
* Zero maintenance
* Auto scalability

### Lambda function
* No server
* Aws charge only for instance running while it doesnt charge to store our code 
* When run the code we pay only for amount of cpu we used
* Scalability and Parallelization
