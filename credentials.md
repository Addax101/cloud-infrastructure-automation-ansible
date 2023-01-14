# Credentials
In order to use Ansible to provision and manage your cloud infrastructure, you will need to configure your cloud provider credentials.

## AWS
* Install the AWS CLI on your machine.
* Run the following command to configure your credentials: aws configure
* Enter your access key and secret key when prompted.
* You can also set up **IAM roles** and **instance profiles** for your EC2 instances, which allows you to manage permissions for your instances without having to use access keys.

## Azure
* Install the Azure CLI on your machine.
* Run the following command to log in to your Azure account: az login
* Follow the instructions to log in to your Azure account.
* You can also set up **Managed Identities** for your Azure resources, which allows you to manage permissions for your resources without having to use access keys.

## GCP
* Install the Google Cloud SDK on your machine.
* Run the following command to log in to your GCP account:
`
