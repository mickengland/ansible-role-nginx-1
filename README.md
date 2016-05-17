NGINX installation for Centos 5-6-7 
=========

Install epel, install nginx and push a index.html file

Example Playbook
----------------
  - hosts: web
    remote_user: centos
    become: yes
    gather_facts: yes

    roles:
      - role: nginx


Author Information
------------------
Michael Lessard - Red Hat
http://twitter.com/michaellessard
