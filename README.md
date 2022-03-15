# kubectl

### Download the latest Kubernetes release
```bash
curl -LO "https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl"
```

### Make the kubectl binary executable
```bash
chmod +x ./kubectl
```

### Move the binary
```bash
sudo mv ./kubectl /usr/local/bin/kubectl
```

### Verify
```bash
kubectl cluster-info
kubectl version
```
