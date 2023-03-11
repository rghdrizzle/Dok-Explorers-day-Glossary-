# Kubernetes
Welcome to Kubernetes glossary 

This glossary covers the most important and relevant terms related to k8s, and each term is defined

| Term | Definition |
| --- | --- |
|Container|A lightweight and portable executable that contains software and all its dependencies. Kubernetes uses containers to package and run applications|
|Pod|The smallest unit of deployment in Kubernetes. It represents a single instance of a running process in a cluster. A pod can contain multiple containers or just one of it|
|Deployment| A Kubernetes resource that manages the creation and scaling of replica sets, which in turn manage the creation and scaling of pods(This is mostly used in k8s deployment)|
|Replica Set|A Kubernetes resource that ensures that a specified number of pod replicas are running at any given time|
|Service|A Kubernetes resource that provides a stable IP address and DNS name for a set of pods, allowing them to be accessed by other components within the cluster or from outside the cluster|
|Node|A physical or virtual machine in a Kubernetes cluster that runs one or more pods|
|Kubernetes API server|The central component that provides a RESTful API for interacting with Kubernetes resources|
|Kubectl|A command-line tool used to interact with Kubernetes clusters and manage Kubernetes objects  (If you are a golang developer , you should know that this cli is made with a cli framework known as cobra in golang)|


We hope this glossary helps you better understand the world of k8s, and enables you to explore these exciting technologies with confidence. If you have any feedback or suggestions for new terms to add to the glossary, please feel free to contribute to the repo
