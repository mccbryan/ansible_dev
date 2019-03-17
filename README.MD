
sudo yum install epel-release
sudo yum install ansible

Wndows configure winrm script
https://github.com/ansible/ansible/blob/devel/examples/scripts/ConfigureRemotingForAnsible.ps1

yum -y install python-devel krb5-devel krb5-libs krb5-workstation

https://argonsys.com/microsoft-cloud/articles/configuring-ansible-manage-windows-servers-step-step/

ansible windows -m win_ping

use group_vars