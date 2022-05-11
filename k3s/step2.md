Using the k3s CLI, it's possible to access `kubectl` and inspect the cluster configuration.

To save time, alias k3s kubectl to k. 

`alias kubectl="k3s kubectl"`{{execute}}

`kubectl cluster-info`{{execute}}

`kubectl get node`{{execute}}

View the pods running with the command:

`kubectl get pods --all-namespaces`{{execute}}
