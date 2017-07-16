# ansible-demo
An Ansible Playbook demonstration to deploy LAMP &amp; host a web app.

Execution Command (put the correct value of IP in 'hosts' inventory file before executing):

If you have setup the key based logins -

``ansible-playbook -i hosts playbook.yml``

If you want to use password based logins -

``ansible-playbook -i hosts playbook.yml --ask-pass``
