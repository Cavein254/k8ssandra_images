The aim of Kubernetes is to provide 100 percent performance. Memory swapping in Kubernetes leads to performance degradation since the swap is located on the hard disk which has slow read-write speeds.

It provides a detailed view of the pods in the cluster including resource utilization and status. It is also useful in deleting, reading logs, and checking the performance of pods within a cluster.

We are going to install the binary version using the commands below:

The k8ssandra development team provide an installation script that simplifies the process of setting up a cluster expecially configuring networks.



Creating the three clusters involves downloading a script from github that will create the nodes and configure the internal network.

You are going to create three clusters. One of the clusters will act as the control plane while the other two will act as the data plane. 






You are going to create three clusters. One of the clusters will act as the control plane while the other two will act as the data plane. 
