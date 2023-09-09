# ISEC6000-Secure-DevOps
Google cloud and Microservice Architecture

##Task 1 

Created isec6000 project and cluster assignment1 for the project with location and node pool.
Authenticated kubectl with assignment1 cluster
The step by step output is shown below:

**Step 1:**

At first login in google cloud console is required. 

Then navigating inside Kubernetes Engine section using the GUI after clicking “Create Cluster” a new cluster is created as shown in figure below.
![img.png](images/img1.png)

Then as shown in figure below we can see the cluster name, location, number of nodes, total CPU and total memory of the cluster that is created.
![img_2.png](images/img2.png)
**Step 2:**

To configure the local environment to use kubectl to interact with the cluster we use the command “gcloud container clusters get-credentials CLUSTERNAME –zone us-central1-c –project PROJECT NAME”. As shown in figure below kubeconfig entry was generated for assignment-1.
![img_1.png](images/img3.png)

