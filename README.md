# codepipeline-simple-project
This is a documentation on how to begin with AWS CodePipeline.

This tutorial outlines the creation of a two-stage CodePipeline, integrating CodeCommit as the source and Elastic Beanstalk for deployment. It involves three main steps: setting up Elastic Beanstalk with a Node.js platform, configuring CodeCommit with necessary IAM permissions, and creating the CodePipeline with manual approval for deployment changes.

There are 3 major steps in this tutorial. 
## Elastic Beanstalk Setup:
1. Create an Elastic Beanstalk application with Node.js platform.
2. Use a newly created IAM role with EC2 access for environment setup.
## CodeCommit Setup:
1. Create a CodeCommit repository and IAM user/group with access.
2. Clone the repository locally and push changes.
## CodePipeline Creation:
1. Set up a CodePipeline with CodeCommit as source and Elastic Beanstalk as deploy stage.
2. Add manual approval stage for deployment changes.
3.  Approve changes for deployment.

