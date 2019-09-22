# Ansible-IIS-Manipulation-Via-WinRM
Useful tips and tricks in order to perform Remote Powershell Connection via Ansible 


# Prerequistes : 
- An Ansible Controller ( CentOs , Redhat , Debian , Ubuntu )  with ansible installed and pywinrm installed ( via pip)
- Windows Machines ( Desktop or Servers ) with Windows Remote Managment Installed ( WinRM) 
   
   Launch this powershell scripts : 
https://raw.githubusercontent.com/ansible/ansible/devel/examples/scripts/ConfigureRemotingForAnsible.ps1

This simple example was executed via Oracle Virtualbox for the controller and some windowds servers.


On the Ansible controller :

ansible-playbook set_to_maintenance.yml -i inventory




