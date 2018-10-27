---
# Ansible Role: Prometheus HAProxy exporter

## Description

An Ansible Role that installs Prometheus [HAProxy exporter](https://github.com/prometheus/haproxy_exporter).

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file.

## Example

Example of playbook with default values.
---yaml
- hosts: haproxy
  roles:
    - webnifico.haproxy-exporter
---

## Acknowledgements

Thanks to [Cloud Alchemy](https://github.com/cloudalchemy) for their various Ansible roles related to Prometheus and monitoring, which were used as examples.
