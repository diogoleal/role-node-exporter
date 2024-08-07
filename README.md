This repository has been migrated to https://codeberg.org/diogoleal/role-node-exporter


Role Name
=========

Install node exporter

```
ansible-playbook -i inventory.txt playbook.yaml
```

Requirements
------------

N/A

Role Variables
--------------

N/A


Dependencies
------------

N/A

Example Playbook
----------------

    - name: install node-exporter
      hosts: nodeservers
      become: yes
      roles:
      - node-exporter


