An ansible role to install kubernetes.

**Role Variables**

.. zuul:rolevar:: install_kubernetes_with_cluster
   :default: True

   If true, installs a Minikube cluster.

.. zuul:rolevar:: minikube_version
   :default: latest

   The version of Minikube to install.
