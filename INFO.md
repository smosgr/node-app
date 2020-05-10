> Reference project to familiarise with technologies and concepts.


# Overview 
- Why NODE JS? 
- What is AWS? 
- What is DOCKER?
- What is K8S?
- AWS CodePipeline/CodeDeploy VS Gitlab CI.

# Steps
Working with Kubernetes (K8s) consists of five main steps:

    1. Develop an application e.g. NodeJS app.
    2. Containerize your application i.e. Docker
    3. Create a kubernetes cluster i.e. AWS
    4. Deploy your container to the cluster. e.g. Terraform, AWS, CI/CD
    5. Expose and scale the cluster. 


# Local machine setup

``
# OSX using Homebrew
brew install awscli https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html

# OSX using Homebrew
brew install kops
```

1. User created with the following IAM roles: 
AmazonEC2FullAccess
AmazonRoute53FullAccess
AmazonS3FullAccess
AmazonVPCFullAccess

2. aws configure --profile xxxxxx

AWS Access Key ID [None]: AccessKeyValue
AWS Secret Access Key [None]: SecretAccessKeyValue
Default region name [None]: us-west-1
Default output format [None]: json

bucket_name=stelios1-kops-state-store
aws s3api create-bucket \
--bucket ${bucket_name} \
--region us-east-1