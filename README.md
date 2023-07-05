# Feature-Toggle_Project
Description

Context:

We have a Dockerized .Net Core 6 Service that we need to Deploy to a production EKS cluster. This is the initial ticket to orchestrate to the existing VON EKS Cluster.

Assumptions is that the code runs in a container and the developer can demonstrate - docker compose etc.

Initially code will remain in Bitbucket with piplines running from GitLab

Reason:

To aid with development and future direction of code → containers → K8s.

Actions:

Contact @Amino  - lead developer for the Feature Flag service

Git Lab for the release project - “feature flag” release

Links to the existing Bit Bucket project

Build docker image

Release to Kubernetes cluster 

Review 

Generate ECR (Container registry)  - Done by Dan?

Amino to store the build container image in EKS 

Provide Amino with the relevant build for docker.

See if we can secure this though API gateway with API keys or cert? Not required though but see how we can secure this so its not just public facing

Generate a design page in confluence to demonstrate how this will be done

Build manually first to get working and then build template

See v360-cs-viab template for eg

Generate new ticket for prod deployment

Help to deploy dockerised container in 

Dev

Staging

Put together documentation on how to repeat this process

Exclusions:

any other change

DoD:

Actions complete

Feature toggles available and can be hit from the environments

Target:

Dev, staging

Inform:
