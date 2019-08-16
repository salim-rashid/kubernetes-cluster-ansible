This is repository for storing Ansible YAML files for automating the provisioning of kubernetes.

This is my preferred way of doing this, it was may not work for you right off the bat because you'll 
to change some configurations.

There are 3 files in the repo as decribed below
    - File name: kubernetes-prerequisities.yml
      Description: Installation & configurations of kubernetes pre-requisities.

    - File name: kubernetes-cluster-initialization.yml
      Description: Installing kubelet, kubectl and kubeadm.

    - Fine name: kubernete-cluster-join.yml
      Description: Joining the nodes to kubernetes cluster.

    - Description: 