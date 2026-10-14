#Create a config.yaml to Path /etc/rancher/k3s/config.yaml with content
disable:
  - traefik
kube-apiserver-arg:
  - "service-node-port-range=80-32767"
