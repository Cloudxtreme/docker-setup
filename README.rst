Docker Setup via Ansible
========================


Quick Start
-----------


To use these playbooks first install Ansible on your local machine::
    
    pip install ansible
   

Populate the ``./hosts`` inventory file with the hosts you want to manage::
    
    echo "127.0.0.1" >> hosts   
   

Run the playbook::
    
    ansible-playbook -u root site.yml
