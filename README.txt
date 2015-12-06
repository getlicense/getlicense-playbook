To run this playbook you need something similar to:

ansible-playbook -i hosts site.yml -e "env=getlicense-dev"
It suppose you have configured your Public Key.

Access with user and password:
ansible-playbook -i hosts site.yml -e "env=getlicense-dev ansible_ssh_pass=[PASSWORD]"
