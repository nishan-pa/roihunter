# roihunter
Project for Roihunter

This Project is having two roles postgresql and Prometheus-grafana and meant to run together in this senario.
Role Prometheus-Grafana is depends on Postgresql


Example Playbook
----------------
``` yaml
---
- hosts: localhost
  roles:
    - Postgresql
    - Prometheus-Grafana
```    
    
############################################

Ansible version tested: 2.3.2.0
Os Tested: Ubuntu 18.04

############################################

Optional task file iptables.yml in Prometheus-Grafana is commented

can enable if need additional security rule to apply

