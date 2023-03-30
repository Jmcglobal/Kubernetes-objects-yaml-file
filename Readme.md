### Kubernetes Yaml Config for :
    Pod 
    replicas
    Service
    Deployment

### Deployment vs replicas.
    Unlike replicaset, deployment have an extra feature "Automatic rolling update with zero downtime" and,
    replicaset is responsible for ensuring the desired number of identical pods are running, while a Deployment is responsible for managing the Replicaset and providing declarative updates to the pods it manages.

### Pod: 

A Pod is a group of one or more containers that are deployed together on a Kubernetes cluster. It is the smallest deployable unit in Kubernetes and is used to ensure that the containers are deployed together and can communicate with each other.

### ReplicaSet: 

A ReplicaSet is a controller that ensures that a specified number of Pod replicas are running at any given time. It is used to ensure high availability and scalability of applications running on Kubernetes.

### Deployment: 

A Deployment is an object in Kubernetes that is used to manage and maintain the desired state of an application. It is used to create, update, and delete Pods and ReplicaSets, and to ensure that the desired number of replicas are running at any given time.