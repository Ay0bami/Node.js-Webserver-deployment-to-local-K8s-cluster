# Node.js-Webserver-deployment-to-local-K8s-cluster

The objective of this activity is to validate the skills of creating, deploying, and exposing containerized applications using Docker and K8s in the docker cluster (kind). 
The activity focuses on hands-on skills of creating, sharing, and using Docker images. It verifies that you can create containerized applications and successfully host it on K8s cluster using the tools

The main steps to be achieved in this task are below. 
- Modify the index.js to print out your name, Student Id and batch. Build docker image. 
- Test the image locally by running the docker container and verifying successful HTTP response from the container 
- Publish the created Docker image on Amazon ECR
- Create local K8s cluster (kind) and verify that you have a functional cluster by displaying the cluster nodes
- Create K8s deployment of your application with 1 pod in application-specific namespace. Verify that Deployment, ReplicaSet and Pod are successfully created. 
- Scale your deployment to 3 pods and verify that ReplicaSet scaled out successfully. 
- Expose your deployment with ClusterIP, verify the application is accessible via port forwarding 
- Expose your deployment with NodePort, verify the application is accessible via public IP and port of your EC2 instance hosting K8s cluster in docker (kind)
