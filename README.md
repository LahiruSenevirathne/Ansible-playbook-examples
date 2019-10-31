**Note all the nodes should be accessable through ssh with ssh keys. [sudo with no password]


## Install Kuberenetes 
Add IPs to hosts file.   
Add Master IP under master master tag.   
Run ansible playbook    
`ansible-playbook install-kubernetes-redhat.yaml -i hosts`   

## Install MySQL 
Add IP to host file under mysql tag.      
Run ansible playbook     
`ansible-playbook install-mysql-redhat.yaml -i hosts`  



