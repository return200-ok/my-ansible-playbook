# Ansible Configuration Settings
Changes can be made and used in a configuration file which will be searched for in the following order:

        ANSIBLE_CONFIG (environment variable if set)

        ansible.cfg (in the current directory)

        ~/.ansible.cfg (in the home directory)

        /etc/ansible/ansible.cfg

# Storing and finding roles
By default, Ansible looks for roles in the following locations:

    in collections, if you are using them

    in a directory called roles/, relative to the playbook file

    in the configured roles_path. The default search path is ~/.ansible/roles:/usr/share/ansible/roles:/etc/ansible/roles.

    in the directory where the playbook file is located
