# ansible-roles
Installation and Configuration for Linux Servers (currently focused on Debian)

* call apache_wsgi role with extra-vars (email is for let's encrypt registration)
  ansible-playbook --limit <your_host> --extra-vars "host=www domain=<your_domain> email=<your_email>" <your_playbook>.yml
