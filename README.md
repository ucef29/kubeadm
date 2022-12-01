# kubeadm

# works with kubeadm v1.15 and up:

```
kubeadm init --config=kubeadm-config.yaml --upload-certs

kubeadm init --control-plane-endpoint 192.168.1.89 --cri-socket /var/run/containerd/containerd.sock --pod-network-cidr 10.200.0.0/16 --upload-certs

```
