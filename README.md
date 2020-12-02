

Udacity Cloud DevOps Capstone Project. Project Overview Blue /green deployment

    Created infrastructure using cloud formation scripts aws cloudformation create-stack --stack-name capstoneinfra  --template-body file://jenkins-server.yml  --parameters file://jenkins-server-parameters.json
{
    "StackId": "arn:aws:cloudformation:us-east-2:821556368364:stack/capstoneinfra/1ed67a00-34a6-11eb-9d90-061cfa87b71e"
}
    Jenkins was setup – Plugins Blue-ocean and Aws-pipeline installed

    Added AWS credentials in Jenkins

    Connected to GitHub https://github.com/SURESH-arch/udacitycapstoneproj5.git

    Created EKS cluster Configured kubectl using CI/CD pipeline

    Created Docker credentials
    
    Lint check failure screenshot attached

    In the final step build the pipeline for docker push and Service Pointing to Blue Replication Controller is build and after approval green pod will run and final step is completed.

