# weblogic-cluster-ansible
This project is for multiple managed server in a cluster with one admin server but two different machines. 


Place the server-jre-8u181-linux-x64.tar.gz and fmw_12.2.1.3.0_wls.jar under roles/setup-weblogic/files/

Change the IP of ansible server as per your server. 

ansible-playbook -i ansible_hosts -vv playbook.yml -K
