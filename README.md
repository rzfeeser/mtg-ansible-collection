# Magic the Gathering - Ansible Collection

Welcome! This is an Ansible collection developed for [https://magicthegathering.io](https://magicthegathering.io).

### Presteps

1. Install Python
    - Debian / Ubuntu - `sudo apt install python3-pip`
    - Windows - Ansible will only run on Linux. From the Windows Store install **Ubuntu 22.04** as part of the **WSL 2**. Then follow the steps for Debian / Ubuntu.

2. Install Ansible
    `python3 -m pip install ansible`

### Setup

1. Install the collection:
    `ansible-galaxy collection install git+https://github.com/rzfeeser/mtg-ansible-collection`
    
2. Try out one of the playbooks located in `playbooks/`
    `ansible-playbook playbook/playbook<example>.yml`
