# Backstage
Platform Engineering, Backstage, Kubernetes, ArgoCD, Docker, GitOps, Helm, GitHub Actions &amp; CI/CD to build IDPs

# Before we begin - let understand a problem scenario

  As Devops Engineer - we automate and deploy stuff (pipelines , IAC , deployments....)  into multiple Environment.

##  As normal Day to Day task - new microservice is introduced into system so as Devops Engineer our task :
    1. Create GitHub Repo for source code
    2. Create Dockerfile and upload into Github Repo.
    3. Create CI pipeline to build and push docker image from the Dockerfile.
    4. Also need to create and configure Docker Registry
    5. Create CD pipeline for deployment into Kubernetes and for that we need to write deployment manifest ( using Helm, ArgoCd)

The above work is done only for one ENV and inorder to do the same work for staging , PROD and other environment . We need to tweek the pipelines and do extra work.

# Now , if we need to do the same work for 10 or 100 micorservice - this will take lot of time .

# So issue with Devops is , Devops is fast but complexities can slow down multiple teams and hence Devops Team become blocker

## So the solution for this is Platform Engineering

************************************************************************************

# PLATFORM ENGINEERING
  **Platform engineering is build on top of Devops.**

  Devops bridges gap between dev and ops team to speed up software deleviery , platform engineering used foundation of Devops to automate and streamline infrastructure management.

  Platformm engineering provides the infrasturture to support collablaration between dev and ops team called **Internal Developer platform**

  ************************************************************************************

  # Internal Developer Platform 

  Self service platform for developers to build / deploy and manage applications removing dependancy on Devops team to do the task manually.

    ************************************************************************************
  # Backstage
  Backstage is open source **IDP**

  'https://backstage.io/docs/overview/what-is-backstage '

*************
