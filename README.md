# AWS S3 Bucket Deletion Using AWS CLI

## Project Overview
This project demonstrates how to delete an Amazon S3 bucket using the AWS Command Line Interface (CLI).

## Objective
To create an Amazon S3 bucket, upload sample objects, delete the objects using AWS CLI, remove the bucket, and verify the deletion through the AWS Management Console.

## Technologies Used
- Amazon Web Services (AWS)
- Amazon S3
- AWS CLI
- Windows Command Prompt

## Procedure

1. Sign in to the AWS Management Console.
2. Open Amazon S3.
3. Create a unique S3 bucket.
4. Upload sample files into the bucket.
5. Install and configure AWS CLI.
6. List all available S3 buckets.
7. List objects inside the selected bucket.
8. Delete objects using the recursive command.
9. Delete the empty S3 bucket.
10. Verify the deletion using AWS Management Console.

## AWS CLI Commands

### Check AWS CLI version
`aws --version`

### Verify AWS identity
`aws sts get-caller-identity`

### List all buckets
`aws s3 ls`

### List bucket objects
`aws s3 ls s3://your-bucket-name/`

### Delete all objects
`aws s3 rm s3://your-bucket-name/ --recursive`

### Delete the empty bucket
`aws s3 rb s3://your-bucket-name`

### Verify bucket deletion
`aws s3 ls`

## Result
Successfully demonstrated the deletion of objects and an empty Amazon S3 bucket using AWS CLI and verified the result through the AWS Management Console.

## Author
Goundla Lasya Priya

B.Tech – 3rd Year, Computer Science and Engineering

Roll Number: 2410030325
