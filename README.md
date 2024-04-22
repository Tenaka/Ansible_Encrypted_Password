The how to guide for Ansible Vault is @
https://www.tenaka.net/post/ansible-vault-for-windows

The files required to encrypt the at rest Windows administrator password used by WinRM and perform a ping or copy contents of a directory.

Windows Creds:
Administrator
ChangeMe1234

Ansible-vault password:
Password1234

Copy file to Ansible/Windows directory and execute the following command:
ansible-playbook -i hosts.ini ping.yml --ask-vault-pass



