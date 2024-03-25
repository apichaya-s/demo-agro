# demo-agro
Create a Helm Chart to deploy the image from the previous step. The chart should support
- Simple deployment (Deployment, Service, Ingress, etc)
- Argo Rollout resources (https://argo-rollouts.readthedocs.io/en/stable) to perform
Canary Deployment and BlueGreen Deployment
The chart should also have flexibility to allow Developers to adjust Values. They can choose to use either simple deployment or Canary or Blue Green without having to rebuild the chart frequently
