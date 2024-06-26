# Kubernetes Metrics Server
Metrics-server aggregates resource consumption data like CPU and memory usage for Kubernetes nodes, pods and containers. These metrics are collected from the API exposed by the Kubelet on each node.

The metrics server is commonly used by other Kubernetes add ons, such as the Horizontal Pod Autoscaler or the Kubernetes Dashboard.
```
$ kubectl apply -f deploy/1.8+/
```
### Usage
```
# Display node metrics
$ kubectl top nodes

# Display pod metrics
$ kubectl top pods
```
### User guide
You can find the user guide in the official Kubernetes documentation.

### Design
The detailed design of the project can be found in the following docs:

Metrics API

Metrics Server

Metrics Server Git Hub

For the broader view of monitoring in Kubernetes take a look into Monitoring architecture
