Task 5 – Build a Kubernetes Cluster Locally with Minikube

Overview
This task involved setting up a local Kubernetes environment using Minikube and deploying a sample application to test the deployment process. The objective was to understand the flow from starting a Kubernetes cluster to accessing the deployed application in a browser.

Steps Followed
1. Starting Minikube
We initialized Minikube, which creates a single-node Kubernetes cluster on the local machine. This acts as our test environment for running Kubernetes workloads without needing a cloud service.

2. Creating the Deployment
A deployment was created in Kubernetes to run multiple replicas of the application. Deployments are useful because they ensure that the required number of application instances (pods) are always running, providing fault tolerance and scalability.

3. Checking Pod Status
We verified that the pods created by the deployment were running successfully. Each pod contains one container running the application.

4. Exposing the Deployment
The deployment was exposed through a Kubernetes Service. This made the application accessible by mapping a port from the Minikube cluster to our local network.

5. Getting the Minikube IP
We retrieved the IP address assigned by Minikube to access the application. This IP acts like the cluster’s public endpoint in our local setup.

6. Accessing the Application
By combining the Minikube IP and the exposed port, we accessed the application in a browser, confirming that the deployment worked correctly.

Outcome
Successfully deployed and accessed a sample application using Kubernetes on Minikube.

Learned about the deployment and service concepts in Kubernetes.

Verified that the pods were running and the application was reachable through the assigned IP address.

