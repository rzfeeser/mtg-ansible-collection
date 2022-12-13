# Magic The Gathering - Ansible Collection

Welcome! This is an Ansible collection developed for [https://magicthegathering.io](https://magicthegathering.io)

Ansible is a framework that runs Python scripts primarily used for for automating configuration (Configuration as Code). So, we'll be the first to admit, it's a little silly to have an Ansible collection that interacts with a service that returns info about Magic the Gathering. However, it's a wonderfully maintained API, open, has support of a massive community, and ultimately a fun way to learn. 

*Note: We are not curators of the MagicTheGathering.io API service. For questions general use questions about the API, see the documentation page at* [docs.magicthegathering.io](https://docs.magicthegathering.io)

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
