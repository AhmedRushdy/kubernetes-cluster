# kubernetes-cluster

## Environment
  - Ubuntu VM on VMWare workstation
## Tools
  - Minikube
  - Docker hub to get the image (linuxacademycontent/store-products:1.0.0)
## Commands 
  ### First To create deployment:
      kubectl apply deployment-defintion.yml
  ### Second is to expose NodePort 
      kubectl expose deployment deploy-replicas --type=NodePort --port=80
