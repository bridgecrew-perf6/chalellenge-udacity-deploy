# Overview

The pipeline process is using CLI tools and CircleCI integration with a Github repository. The tools used are detailed below:

## AWS CLI

Used to connect to S3 service and deploy the frontend after a successful build.

## AWS EB CLI

Used to connect to Elastic Beanstalk and send the backend code online to Elastic Beanstalk service.

## GitHub repository

A private monorepo was created in the url: https://github.com/kevinfarias/chalellenge-udacity-deploy. This way, it is possible to connect with CircleCLI to make the deployment automatically work.

## CircleCI

Popular CI/CD tool used to integrate the testing, building and deploying pipeline, testing all the parts and sending it automatically if everything runs fine.
