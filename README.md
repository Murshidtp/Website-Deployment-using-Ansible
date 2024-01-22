# Apache Website Deployment

This project automates the deployment of a website on an Apache server using Ansible.

## Prerequisites

1. Ansible installed on the control machine.
2. SSH access to the target server with sudo privileges.
3. Inventory file configured with your server details.

# Ansible Installation

This guide provides instructions on how to install Ansible on your control machine.

```bash
   sudo apt update
   sudo apt install ansible -y
   ```
## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Murshidtp/Website-Deployment-using-Ansible.git
   cd Website-Deployment-using-Ansible
   ```
2. Update the inventory file (/etc/ansible/hosts) with your server details.
3. Edit the website_deployment.yml playbook to customize paths and settings.
4. Run the Ansible playbook:
   
     ```bash
   ansible-playbook -i /etc/ansible/hosts website_deployment.yml
   ```

