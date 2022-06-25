# Deploying MS SQL Server to Windows 2019 with Ansible

## Prerequisites

- Install pip modules: `python3 -m pip install --upgrade -r requirements.txt`
- Install Ansible Collections: `ansible-galaxy collection install -r ./collections/requirements.yml`
- Modify the inventory to meet your environment

## Running the Playbook

`ansible-playbook -i inventory deploy-mssql.yaml`