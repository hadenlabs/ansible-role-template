# How to use this project

## Generate file `requirements.yml`

```yaml
- name: hadenlabs.ansible-role-name
  src: git+https://github.com/hadenlabs/ansible-role-template
  version: 0.0.0
```

### Execute:

```bash
ansible-galaxy install -r requirements.yml
```

# How to use this project

```bash
ansible-galaxy install hadenlabs.ansible-role-name
agr 'ansible-role-template' 'new-project'
agr 'AnsibleRoleTemplate' 'NewProject'
agr 'ansible-role-name' 'project'
```

Full working examples can be found in [examples](/examples) folder.

# Links

- See [Configure](/docs/usage/configure.md)
