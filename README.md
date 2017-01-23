# iosxr-j2
Jinja2 template for Ansible

Directory structure:
/etc/ansible
├── group_vars
│   └── all
├── hosts: localhost ansible_connection=local
└── roles
    ├── gre
    │   ├── tasks
    │   │   └── main.yml
    │   ├── templates
    │   │   └── mplsogre.j2
    │   └── vars
    │       └── main.yml
    └── vrf
        ├── tasks
        │   └── main.yml
        ├── templates
        │   └── default.j2
        └── vars
            └── main.yml


