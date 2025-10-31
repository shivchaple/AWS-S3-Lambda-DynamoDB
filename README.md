# AWS-S3-Lambda-DynamoDB
Automatically Store S3 Files Metadata in DynamoDB Using Lambda: Developed a serverless solution using  AWS Lambda to automatically capture and store file metadata (like name, size, and timestamp) from S3  uploads into a DynamoDB table for efficient data tracking and querying. 

Step By Step How I performed this project 
Step1: Create a S3 bucket 
Step2: Create a DynamoDB table
Step3: Created IAM role >> Use cae- Lambda >> Permissions- DynamoDB Full access and cloudwatch full access
Step4: Create AWS Lambda function >> Author from scrath >> Name of Function >> Runtime - Python >> Arrached role ^^
Step5: Add trigger to this function >> select bucket >> Event type - PUT,POST,COPY etc
Step6: On code option write a python using boto3
