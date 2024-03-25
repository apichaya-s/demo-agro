# demo-agro
Use ArgoCD to deploy this application. To follow GitOps practices, we prefer to have an ArgoCD application defined declaratively in a YAML file if possible.

## Usage

Create Argo project
```
kubectl apply -f applications/demo-prod/argo-project.yaml
```

Create Argo applicaiton
```
kubectl apply -f applications/argo-application.yaml
```

