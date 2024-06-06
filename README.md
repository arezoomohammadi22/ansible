Run the Playbook
``bash
ansible-playbook playbooks/create_users.yml -u username --become -kK
``
-k prompts for the SSH password.
-K prompts for the sudo password.
