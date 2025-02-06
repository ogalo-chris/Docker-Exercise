# This YAML file defines a ReplicaSet for a Kubernetes cluster.
# 
# apiVersion: Specifies the API version (apps/v1) used to create the ReplicaSet.
# kind: Indicates that this resource is a ReplicaSet.
# metadata: Contains metadata about the ReplicaSet, including its name and labels.
#   name: The name of the ReplicaSet.
#   labels: Key-value pairs to categorize the ReplicaSet.
# spec: Defines the desired state of the ReplicaSet.
#   replicas: The number of pod replicas to maintain for high availability.
#   selector: Specifies how to identify the pods managed by this ReplicaSet.
#     matchLabels: The labels that the pods must have to be managed by this ReplicaSet.
#   template: Describes the pods to be created by the ReplicaSet.
#     metadata: Contains metadata about the pods, including their labels.
#       labels: Key-value pairs to categorize the pods.
#     spec: Defines the specification of the containers within the pods.
#       containers: A list of containers to be run in the pods.
#         - image: The Docker image to use for the container, in this case, nginx version 1.14.2.
