Using the k3s CLI, it's possible to access `kubectl` and inspect the cluster configuration.

`k3s kubectl cluster-info`{{execute}}

`k3s kubectl get node`{{execute}}

View the pods running with the command:

`k3s kubectl get pods --all-namespaces`{{execute}}

To save time, alias k3s kubectl to k. 

`alias k="k3s kubectl"`{{execute}}

You can now use

`k get pods --all-namespaces`{{execute}}
