# blockchain
Deployment of Blockchain with Quorum protocol. 


## Resources 
- [Forked racecourse project](https://github.com/calbritt/racecourse)
- [Docker Registry](https://hub.docker.com/repository/docker/calbrit1/kaleidoproject/general)
- All images used are located in docker registry


## Instructions

```
    minikube start 
    minikube addons enable ingress
    alias kubectl="minikube kubectl --"
    kubectl apply -f racecourse
    kubectl apply -f k8s    

    kubectl get all ## verify all resources have spun up correctly 

    ## fetch minikube service url for web app 
    minikube service --url racecourse-service
```
    account id node 1: 0xe09e1488D4aAb26B9E3cf6144Bfb3018C91C2816
