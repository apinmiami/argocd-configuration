# Folder: dev
  To store all pod configuration files

# Argo config file

- `project: default` helps to group all pods into project
- `repoURL:` git hub repo which needs to be synced to argocd
- `namespace: application` deploy all the pods in specified namespace
- `CreateNamespace=true` creates the namespace if it is not exist
- `selfHeal: true` helps to overwrite the changes done manually and maintain the desired state
- `prune: true` if any changes like delete or rename done in repo will reflect in cluster by enabling this option