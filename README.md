:construction: ***DEVELOPING*** :construction:

# **template-ansible-role**

![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=flat&logo=ansible&logoColor=white)
![GitHub License](https://img.shields.io/github/license/ironwolphern/ansible-role-bastion)
![GitHub release (with filter)](https://img.shields.io/github/v/release/ironwolphern/ansible-role-bastion)
![GitHub pull requests](https://img.shields.io/github/issues-pr/ironwolphern/ansible-role-bastion)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/ironwolphern/ansible-role-bastion)
![GitHub issues](https://img.shields.io/github/issues/ironwolphern/ansible-role-bastion)
[![Ansible Lint](https://github.com/ironwolphern/ansible-role-bastion/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/ironwolphern/ansible-role-bastion/actions/workflows/ansible-lint.yml)
![Dependabot](https://badgen.net/github/dependabot/ironwolphern/ansible-role-bastion)

A brief description of the role goes here.

## *Requirements*

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## *Role Variables*

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

This is a list of required and optinal variables and parameters for this role:

| **Parameter** | **Description** | **Type** | **Default** | **Options** | **Required** |
|---------------|-----------------|----------|:-----------:|:-----------:|:------------:|
| variable_input | description | type | default value |  | yes/no |

## *Dependencies*

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## *Example Playbook*

This is an example of use role with optionals and required parameters:

*playbook-file.yml*
```yaml
    - hosts: example
      roles:
        - example-role
      vars:
        var_input_1: XXXXXXXX
        var_input_2: 00000000
```

These are some examples of the use of this playbook with the different tags that can be used in this role:

Install and configure for example
```bash
  ansible-playbook -i inventory playbook-file.yml
```
## *License*

MIT

## *Author Information*

This role was created in 2023 by:

- Fernando Hernández San Felipe (ironwolphern@outlook.com)
