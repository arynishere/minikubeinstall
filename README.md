

# Minikube Setup with Docker using Ansible

This repository contains an Ansible playbook to set up Minikube with the Docker driver on Ubuntu 22.04.

## Minikube System Requirements
- 2 GB RAM or more
- 2 CPU / vCPU or more
- 20 GB free hard disk space or more
- Docker / Virtual Machine Manager – KVM & VirtualBox

## Instructions

1. Clone this repository to your local machine.

```bash
git clone https://github.com/arynishere/minikubeinstall.git
```

2. Navigate to the repository directory.

```bash
cd minikubeinstall
```

3. Run the Ansible playbook.

```bash
ansible-playbook minikube.yml -K
```

You will be prompted for the sudo (root) password.

4. After the playbook completes, Minikube with Docker should be installed on your machine.

## Usage



- Verify Minikube status.

```bash
minikube status
```

- Verify kubectl installation.

```bash
kubectl version -o yaml
```

## Troubleshooting

If you encounter any issues, refer to the troubleshooting section in the playbook or open an issue on GitHub.

