### Rotten Potatoes

#### Exercise app to learn about kubernetes


### Using K3D


Steps:

```bash
k3d cluster create rotten-potatoes-cluster --servers 1 --agents 2 -p "8080:30000@loadbalancer"

kubectl get nodes

kubectl apply -f ./k8s/
```