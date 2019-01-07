# ansible_password_managemant
A test in using Ansible to manage the linux estates passwords.

``` export ANSIBLE_HOST_KEY_CHECKING=False ; ansible-playbook -vvv -i inventory/dmz main.yaml --extra-vars "target=all" --ask-become-pass ```
