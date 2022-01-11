# Kubernetes
### Vagrant
https://www.notion.so/Vagrant-58041e5dc53e4172a5fed69bed360d2e

### Container-Runtime
- Docker Install
https://www.notion.so/Docker-Install-415afc1a3ee142c29b62620619113ca6

- CRI-O Install
https://www.notion.so/CRI-O-Install-38046914df054e5fb073e13ed63c67fd

- Containerd Install
https://www.notion.so/Containerd-Install-82d1df4ba21d432481b8c61ded5fdd8c

### Kubernetes
- kubernetes install, kubernetes version upgrade & downgrade, kubernetes node add & delete, 명령어 자동 완성
https://www.notion.so/d6e4e471590a45eaadec5b98c7c6f43d

### CNI 
- calico
```
curl https://docs.projectcalico.org/manifests/calico.yaml -O
kubectl apply -f calico.yaml
```
- weavenet
```
kubectl apply -f "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 | tr -d '\n')"
```
### Metallb
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-3.-Kubernetes-Network-MetalLB

### Rook-Ceph 
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-4.-Kubernetes-Storage-Rook-Ceph

### Monitoring
- Prometheus & Grafana
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-7.-Kubernetes-Monitoring---Prometheus,-Grafana-%EA%B5%AC%EC%B6%95

### log
- Elastic Search & Loki & ?

### Jenkins

### ArgoCD
https://www.notion.so/ArgoCD-8474072a10c045e8ae43130ea5aa2f3f

### K6 load test
https://www.notion.so/k6-64e2e91bb8364d7d8ad66305419079eb

### Metric server
https://www.notion.so/Metric-Server-0f527ff6cd97435784d6fb54dc3df46f

### K9s
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-10.-K9s

### EKS Install
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-8.-Kubernetes-Cluster-with-EKS

### GKE Install
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-9.Kubernetes-Cluster-with-GKE

### Kubernetes multi cluster management
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-Kubernetes-Multi-Cluster-Management

### Minikube
https://github.com/ndiepray/CCCR_FLFD/wiki/%5BInfra%5D-Minikube-Install

### K3s Install
https://www.notion.so/K3s-ada875b7491645c1afdf328d17eba820
