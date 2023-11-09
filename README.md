# Ansible Masterclass to cover RED HAT CERTIFIED SPECIALIST IN ANSIBLE AUTOMATION exam (EX407)
A project to setup a Kubernetes cluster using Ansible + AWS

## Steps
├── Provisioning
│   ├── Create Security Groups
│   ├── Create EC2 instances in AWS
│   ├── Add created hosts IP to inventory
│   └── Wait pipeline until SSH is ready
│
├── Setup Kubernetes/K8S
│   ├── Install k8s to all hosts
│   ├── Create cluster in Master host w/ CA & Network
│   ├── Join Workers hosts to created cluster
│   ├── Setup helm 3
│   └── Setup Monitoring Stack in Master host- Prometheus, Grafana, Alertmanager, Node-Exporter, etc.
│
├── Deploy app v1
│   ├── Setup app structure
│   └── Apply k8s deployments & services
├── Deploy app v2
│   ├── Setup app structure
│   ├── Apply new version deployments & services
│   ├── Scale down old version
│   └── Inactive old version after success deployment
└── Done