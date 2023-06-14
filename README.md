## AndrewGodGivens /ansible_prometheus_nginx_exporter 
============

An Ansible role which installs and configures Prometheus nginx_exporter on Linux

============

## Requirements

Ansible 2.8+

============

## Role Variables

You can see all vars in defaults/main.yml vars file.

## Example Playbook

```yaml
- name: Ensure prometheus_nginx_exporter
  hosts: prometheus_nginx_exporters
  remote_user: root

  roles:
    - prometheus_nginx_exporter
  
```
