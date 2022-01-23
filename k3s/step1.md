Download the initial release from Github using `curl -LO https://github.com/rancher/k3s/releases/download/v0.1.0/k3s; chmod +x k3s; mv k3s /usr/local/bin/`{{execute}}

Download the initial release from Github using `curl -LO https://github.com/kubernetes/kops/releases/download/$(curl -s https://api.github.com/repos/kubernetes/kops/releases/latest | grep tag_name | cut -d '"' -f 4)/kops-linux-amd64;chmod +x kops-linux-amd64;sudo mv kops-linux-amd64 /usr/local/bin/kops`{{execute}}




Once downloaded, you have everything you need to start the cluster using the command `k3s server`{{execute T1}}

You now have a single node Kubernetes cluster.