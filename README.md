# Ansible
---
- name: update 
  hosts: all
  tasks: 
   - name: update service
     yum:
      name: httpd
      state: latest
   
