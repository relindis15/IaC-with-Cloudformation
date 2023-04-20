# IaC-with-Cloudformation

## Cloudformation was used to create an S3 bucket using the following commands

*creating a stack

aws cloudformation deploy --template-file s3-template.yaml --stack-name relindis-stack

*code to check if stack was created

-aws cloudformation describe-stacks --stack-name relindis-stack

* command to delete stack
aws cloudformation delete-stack --stack-name relindis-stack

*s3 bucket created image

<img width="926" alt="s3 bucket" src="https://user-images.githubusercontent.com/114790551/233234259-3e9302d2-7338-4e41-a88c-32bcff4fdcdf.png">

*stack created image

<img width="953" alt="cloudformation stack" src="https://user-images.githubusercontent.com/114790551/233234434-eac12d9b-71f6-4310-b9fc-98c9a9c59145.png">
