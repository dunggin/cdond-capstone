# UDACITY CLOUD DEVOPS ENGINEER - CAPSTONE PROJECT

Github URL: https://github.com/dunggin/cdond-capstone/tree/dev
ELB URL: http://af230c219017044edba0ce128d786813-527420098.us-east-1.elb.amazonaws.com/hello


## Tools

Project is created with:

- CirleCI
- CloudFormation
- AWS - EKS
- Kubernetes
- ECR - Elastic Container Registry
- GitHub


## Linting using Pylint and Hadolint

Linting is used to check if the Application and Dockerfile is syntactically correct.
This process makes sure that the code quality is always as good as possible.


## Usage

- Setup and Configure CirceCI account with Github and AWS Credentials
- Create ECR repo via AWS console (see more https://docs.aws.amazon.com/AmazonECR/latest/userguide/repository-create.html).
- AWS : create an IAM user with AWS access key to store in your local
- Configure enviroment variables AWS_DEFAULT_REGION, AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_SESSION_TOKEN in your CircleCI account (see more https://circleci.com/docs/set-environment-variable/#set-an-environment-variable-in-a-context)
- Once your project is configure with your CircleCI pipeline, you could trigger the workflow run by committing code or hitting a PR