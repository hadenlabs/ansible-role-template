<!-- Space: Projects -->
<!-- Parent: AnsibleRoleTemplate -->
<!-- Title: Examples AnsibleRoleTemplate -->
<!-- Label: Examples -->
<!-- Include: ./../disclaimer.md -->
<!-- Include: ac:toc -->

## packages

To run this playbook with default settings, for install package like this:

generate file `requirements.yml`

```yaml
- name: hadenlabs.ansible-role-template
  src: git+https://github.com/hadenlabs/ansible-role-template
  version: /main
```

```yaml
- hosts: all
  roles:
    - role: hadenlabs.ansible-role-template
      become: true
      vars:
        ansible-role-template_owner: ubuntu
```
