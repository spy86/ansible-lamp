# ansible-lamp
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Getting Started

  1. Install [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  2. Install [Vagrant](https://www.vagrantup.com/downloads.html)
  3. Install [Ansible](http://docs.ansible.com/ansible/latest/intro_installation.html)
  4. Run the following command to install the necessary Ansible roles: `$ ansible-galaxy install -r requirements.yml`
  5. Run the following command to deploy role: `$ ansible-playbook -i inventory playbook.yml`
