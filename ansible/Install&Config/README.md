This playbook is Install Version 7.x on Centos 7  <br />
The playbook was built and tested on Centos 7, for ELK versions 7.x <br />

Configuration:  <br />
1-Edit your Ansible hosts file ('/etc/ansible/hosts') and add an 'elkservers' <br />
2-clone this repo <br />
3-Cd into the directory, and run: ansible-playbook site.yml<br />

elk==>Install Elasticsearch,Kibana and Nginx 