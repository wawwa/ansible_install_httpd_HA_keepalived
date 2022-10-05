# Ansible. Install and configure httpd, HAProxy, keepalived
PING ALL


ansible-playbook playbook_ping_all.yml



ROLES

ansible-playbook httpd.yml    
ansible-playbook haproxy.yml    
ansible-playbook keepalived.yml    



ROLES ALL  

ansible-playbook web_haproxy_ha.yml
