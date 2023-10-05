# clamav-on-satellite6
This project contains Ansible roles and playbooks for installing and configuring ClamAV on a Satellite server. It's designed for Red Hat Satellite 6.13 and similar environments.

# Contributors

A list of individuals who have contributed to this project:

- Jayson Harper - jayharper77@gmail.com

This project contains Ansible roles and playbooks for installing and configuring ClamAV on a Satellite 6 server. It's designed for Red Hat Satellite 6.13 and similar environments.

## Structure

The project is structured as follows:

- `inventory/`: Contains inventory files. Replace the placeholders with your actual server details.
- `roles/`: Contains roles, including tasks for installing and configuring ClamAV.
- `playbooks/`: Contains the main playbook that applies the ClamAV role to the Satellite 6 servers.
- `ansible.cfg`: Ansible configuration file that specifies the paths to the inventory and roles directories.

## Usage

1. Clone the repository to your local machine.
2. Update the `inventory/dev.ini` file with your actual server details.
3. Navigate to the `ansible_project` directory and execute the playbook:

```bash
cd clam-on-satellite
ansible-playbook playbooks/clamav_install.yml
