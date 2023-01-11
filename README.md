# Ansible Role Template for Molecule Testing

This repository provides a Cookiecutter template for creating an Ansible role that follows best practices and conventions, and is ready for testing with Molecule. The template sets up a directory structure, and testing framework that allows for easy development, testing, and deployment of Ansible roles. The goal is to speed up the role creation process and make it easy to test and maintain your ansible role.

## Customization

You can change the role and scenario name to match your desired role name.

## Usage

1.  Install [Cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html)

> **note** `cookiecutter` is bundled with [ansible molecule](https://molecule.readthedocs.io/en/latest/).

2.  Clone the repository
    
    `git clone https://github.com/<your_username>/molecule-template-role.git`
    
3.  Run Cookiecutter to create the role
    
``` bash
$ cookiecutter molecule-template-role # this repo
You have downloaded /<home_directory>/.cookiecutters/molecule before. Is it okay to delete and re-download it?
[yes]: yes
role_name [OVERRIDEN]: <role_name example: role_example_name>
scenario_name [default]: <enter>
```
    
4.  After the process is completed navigate to the created directory and start using the role, and customize it to fit your needs
5.  If you would like to use molecule to test the role please refer to [molecule documentation](https://molecule.readthedocs.io/en/latest/)


