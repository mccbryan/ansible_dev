
sudo yum install epel-release
sudo yum install ansible

Wndows configure winrm script
https://github.com/ansible/ansible/blob/devel/examples/scripts/ConfigureRemotingForAnsible.ps1

yum -y install python-devel krb5-devel krb5-libs krb5-workstation

https://argonsys.com/microsoft-cloud/articles/configuring-ansible-manage-windows-servers-step-step/

ansible windows -m win_ping

use group_vars

ansible-vault create /etc/ansible/group_vars/windows.yml

chown the windows.yml to the sa.ansible account

ansible -m win_ping windows --ask-vault-pass

https://docs.ansible.com/ansible/latest/user_guide/vault.html#what-can-be-encrypted-with-vault

