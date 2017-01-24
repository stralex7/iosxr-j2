# iosxr-j2
Jinja2 template for Ansible

# Quick howto
1. Install Ansible, I use latest ubuntu. The official installation guide is [here](http://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-apt-ubuntu)
2. Modify /etc/ansible/hosts to include: `localhost ansible_connection=local`
3. Clone this repository
4. Modify `roles/gre/vars/main.yml` to match your setup
5. Execute ansible-playbook playbook.yml
6. Configuration files named `hostname.cfg` will be generated in `/tmp`, you can modify the path in `roles/gre/tasks/main.yml`

The template itself is located in `roles/gre/templates`. You can use this for autogenerating configuration files based on your requirements.


