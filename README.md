# ansible-playbook-AzureVM-WordPress

```
I am using Microsoft Azure, and targeting this provider as it allows me to launch virtual machines and interact with them without having too much configuration overhead.
```

```
ansible-galaxy collection install azure.azcollection
pip3 install -r ~/.ansible/collections/ansible_collections/azure/azcollection/requirements-azure.txt
az login
az account list --output table
az account set --subscription <subscription_id>
ansible-playbook -i hosts site.yml
```
