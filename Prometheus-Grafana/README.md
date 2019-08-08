Prometheus Grafana
=========
 
This role will create dockers with prometheus, Grafana, Postgresql metrics_exporter, nginx to reverse proxying prometheus


Requirements
------------
Docker is installed using role Postgresql. So it should run first

Role Variables
--------------
All variables are specified in defaults

Dependencies
------------


Example Playbook
----------------
Pretty straigh forward.
``` yaml
---
- hosts: localhost
  roles:
    - Prometheus-Grafana
```



Author Information
------------------

This Role is created for ROIHUNTER Project
