# ADT_DevOps_4_CloudFormation_CreateS3_Deploy

This example repo uses a basic pipeline (workflow in GitHub Actions) to create an S3 bucket in AWS and configure it to host a static web app. 
This is done via the yml file, via AWS CloudFormation. 
The pipeline/workflow then copies (deploys) the website files from the repo 'website' folder to the new S3 bucket, putting the website live.
