# cloud-infrastructure-automation-ansible
This repository contains the code and documentation for automating the provisioning and management of cloud infrastructure using Ansible.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
* Ansible
* AWS CLI (if using AWS)
* Azure CLI (if using Azure)
* Google Cloud SDK (if using GCP)
## Installing
* Clone the repository `git clone https://github.com/Addax101/cloud-infrastructure-automation-ansible.git`

* Install Ansible and the appropriate CLI for the cloud provider you are using.

* Configure your cloud provider credentials by following the instructions in the `credentials.md` file in the repository.

* Run the playbook to provision the infrastructure: `ansible-playbook -i inventory.yml main.yml`
* Use the cloud provider's web console or the CLI to verify that the infrastructure has been provisioned.

## Managing the infrastructure
* Make changes to the playbook or inventory files to reflect the desired state of the infrastructure.

* Run the playbook again to apply the changes: `ansible-playbook -i inventory.yml main.yml`
## Troubleshooting
You can check the status of the infrastructure by running the `debug` module:
`ansible -i inventory.yml -m debug -a "var=hostvars[inventory_hostname]" all`

## Built With
* Ansible - Configuration management tool
* AWS (or Azure, GCP) - Cloud provider
## Authors

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
GPS
