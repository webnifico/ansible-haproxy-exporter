# Ansible Role: Prometheus HAProxy exporter

[![Build Status](https://travis-ci.com/webnifico/ansible-haproxy-exporter.svg?token=ya2jwEdwbzxuostpa2Zr&branch=master)](https://travis-ci.com/webnifico/ansible-haproxy-exporter)

## Description

Ansible Role for installing Prometheus [HAProxy exporter](https://github.com/prometheus/haproxy_exporter).

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file.

## Example

Example of playbook with default values.

```yaml
- hosts: haproxy
  roles:
    - webnifico.ansible-haproxy-exporter
```

## Acknowledgements

Thanks to [Cloud Alchemy](https://github.com/cloudalchemy) for their various Ansible roles related to Prometheus and monitoring, which were used as examples.
