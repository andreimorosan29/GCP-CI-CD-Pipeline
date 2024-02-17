# GCP-CI-CD-Pipeline
This is a project to showcase how to build a CI/CD pipeline in Google Cloud.

# Definitions and Intro

_What is Continuous Integration (CI) ?_

Integration issues are identified early in the software development process through Continuous Integration (CI), which involves developers regularly merging code into a common repository, ideally multiple times daily. Each integration is validated by an automated build and tests to maintain a single, unbroken code repository.

+ Developers all submit code changes to a central branch in a shared repository. 
+ Building is automated through a CI service that compiles the code and conducts tests when new changes are made.
+ Tests are carried out in an environment similar to the production setup.
+ The build process includes self-testing mechanisms.
+ Timely feedback is crucial, with integration problems being detected quickly.
+ Any issues that arise are promptly addressed by the responsible developers.
+ Successful builds can be automatically deployed to testing or production environments.

_What is Continuous Delivery/Deployment (CD)?_

Continuous Delivery involves the automatic building, testing, and preparation of code changes for deployment to production. In this practice, each change is made ready for release, although the decision to deploy to production requires manual intervention.

+ Similar to Continuous Integration, every code modification initiates an automated build and testing sequence.
+ The result of the automated build is saved in a repository and can be promptly deployed to any setting.
+ Builds are automatically prepared for deployment, containing application code, configuration files, scripts, etc.
+ The step of deploying to production is done manually to give the team control over releasing new versions.
+ Real-time monitoring in production allows quick detection and resolution of any post-deployment issues.

This process, known as Continuous Deployment (or CD), goes a step beyond by automatically sending each approved change to production after passing automated build and tests, without requiring manual approval. It is ideal for low-risk applications that have thorough automated testing in place.

**Summary**

Continuous Integration (CI): Build and test code automatically whenever changes are committed.
Continuous Delivery (CD): Automated build, test and preparation of deployment-ready releases.
Continuous Deployment (also CD): Automatically deploy successful builds to production with no human intervention.
