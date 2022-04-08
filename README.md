# kubernetes-cluster

## Environment
  - Ubuntu VM on VMWare workstation
## Tools
  - Minikube 
## Commands 
  ### First To create deployment:
      kubectl apply deployment-defintion.yml
  ### Second is to expose NodePort 
      kubectl expose deployment deploy-replicas --type=NodePort --port=80
