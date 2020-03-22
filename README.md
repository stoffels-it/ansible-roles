# ansible-roles
Installation and Configuration for Linux Servers (currently focused on Debian)

* call apache_wsgi role with extra-vars like:
  ansible-playbook --limit <your_host> --extra-vars "host=www domain=<your_domain>" <your_playbook>.yml
