# ansible-roles
Installation and Configuration for Linux Servers (currently focused on Debian)

* call apache role from a playbook with extra-vars in commandline: (email is for let's encrypt registration)
  ansible-playbook --limit <your_host> --extra-vars "host=www domain=<your_domain> email=<your_email>" <your_playbook>.yml
