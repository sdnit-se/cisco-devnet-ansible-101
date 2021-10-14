# Ansible101

## Environment Setup
 - `python3 -m venv venv`
 - `source venv/bin/activate`
 - `pip install --upgrade pip`
 - `pip install -r requirements.txt`
 - `ansible-galaxy collection install -r requirements.yml`


## Installation Documentation
https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

## Network Documentation
https://docs.ansible.com/ansible/latest/network/getting_started/index.html

## Facts
`ansible iosxe -m gather_facts`

`ansible iosxe -m cisco.ios.ios_facts`

## Jinja2 documentation
`https://jinja.palletsprojects.com/en/3.0.x/templates/`

## IOS-XE module documentation
`https://galaxy.ansible.com/cisco/ios`
`https://developer.cisco.com/learning/modules/intro-ansible-iosxe`

## AWX / RedHat Ansible Automation Platform
`https://www.ansible.com/products/awx-project/faq`
`https://www.ansible.com/products/automation-platform`

