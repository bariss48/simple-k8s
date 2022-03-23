# k8s basics
# Reference
## Docker and Kubernetes: The Complete Guide ( Stephen Grider Course )

### Clone repository
```
$ git clone https://github.com/bariss48/simple-k8s.git
```
### Minikube start
```
$ minikube start
```
### apply changes with kubectl
```
$ kubectl delete -f k8s/
$ kubectl apply -f k8s/
```
#### after all of this your all pods must be 'running' status.
<img width="646" alt="pods" src="https://user-images.githubusercontent.com/50153950/159661424-68b1060e-e642-4288-bf2a-a138fc37623e.png">

### Minikube dashboard
```
$ minikube dashboard
```
<img width="1549" alt="dashboard" src="https://user-images.githubusercontent.com/50153950/159661807-ca2fe47f-20d8-4329-a49a-39b1a1acbf80.png">

### Architecture of services
<img width="1126" alt="Ekran Resmi 2022-03-23 12 01 53" src="https://user-images.githubusercontent.com/50153950/159662134-dc2f7063-a545-476a-a494-78c55e2169df.png">