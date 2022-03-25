# install-Lamp-stack
 This repo is to
	1- install Apache, PHP and MySql packages using ansible
 	2- start and enable them all
	3- permit the web traffic on port 80 and 443 on the firewalld
	4- copy a sample php page (already created) from ansible server to the lamp stack machine.
**************************************************************************************************

The setup environment:
I have 2 local virtual machines
	1 ==> controller with ansible installed to push the configuration
	2 ==> Target machine to receive the configuration from the ansible server. ip(192.168.10.26)
****************************************************************************************************

Commands required to run the playbook
---------------- ansible-playbook -i hosts my-playbook.yml-------------------

***************************************************************************************************

