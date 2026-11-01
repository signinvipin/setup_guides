# setup_guides

Step-by-step install and configuration notes for common DevOps tools, written from hands-on setups on AWS EC2 and Azure VMs.

## Guides
| Guide | Covers |
|---|---|
| [ansible_setup.txt](./ansible_setup.txt) | Ansible control node, SSH key access to remote servers, running playbooks |
| [jenkins_setup.txt](./jenkins_setup.txt) | Jenkins server installation and initial setup |
| [nexus_setup.txt](./nexus_setup.txt) | Sonatype Nexus repository manager |
| [docker_setup.txt](./docker_setup.txt) | Docker installation on an EC2 VM |
| [elk_setup.txt](./elk_setup.txt) | Elasticsearch, Kibana and Logstash |
| [portainer_setup.txt](./portainer_setup.txt) | Portainer CE with Docker |
| [jupyterhub_setup.txt](./jupyterhub_setup.txt) | JupyterHub on Kubernetes (AKS), including HTTPS |
| [terraform_azurecli_setup.txt](./terraform_azurecli_setup.txt) | Terraform and Azure CLI setup |
| [encryption_azure_storage_setup.txt](./encryption_azure_storage_setup.txt) | Customer-managed encryption for an Azure storage account |

## Notes
- IP addresses are partially masked with `xx` (for example `3.16.xx.xx`) and secrets are replaced with `xxxx`. Use your own values.
- The Ansible playbooks used in the guides are in the [ansible](https://github.com/signinvipin/ansible) repository.
