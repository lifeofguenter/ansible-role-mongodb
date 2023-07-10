# lifeofguenter.mongodb

An Ansible role that installs and configures the community edition of MongoDB on
Debian-like systems.

## Requirements

none

## Role Variables

Available variables are listed below, along with default values:

```yaml
mongodb_version: '5.0'
```

## Dependencies

none

## Example Playbook

```yaml
- hosts: webservers
  roles:
    - { role: lifeofguenter.mongodb }
```

## License

**MIT**, see the [LICENSE file](LICENSE) for details.

## Author Information

[Günter Grodotzki](https://www.lifeofguenter.de)
