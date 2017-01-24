# iosxr-j2
Jinja2 template for Ansible

# Install Ansible
1. http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu
2. Modify /etc/ansible/hosts to include
    localhost ansible_connection=local
3. Clone this repository
4. Modify roles/gre/vars/main.yml to match your setup
5. Execute ansible-playbook playbook.yml
6. Configuration files <hostname>.cfg will be generated in /tmp, you can modify that in roles/gre/tasks/main.yml


