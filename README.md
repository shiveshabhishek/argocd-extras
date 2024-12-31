# argocd-extras
This repo contains the file `all-in-one-except-crds.yaml`, which can be used to install argocd in a new namespace.<br/>
The CRDs are disabled, and namespace `sa-argocd` is used. Also, the ClusterRole and ClusterRoleBindings have been tweaked a little to make it compatible to be deployed on another namespace in a cluster where on argocd instance is already running.

If you use this file then, no need to use the files under `argo-extra-cr-crb` directory.