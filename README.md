# ansible-assignment-1
Ansible Playbook Assignment 1 for CNIT-381

## Description of Playbook
The following playbook will configure the hostname of the devices specifed in the ```inventory.ini``` files under the ```[routers]``` section. Next, the playbook will add the interface description as specified in the ```inventory.ini``` file for the devices. After this, the playbook performs verification tasks to ensure that the hostname and interface description was configured correctly. Depending on if it was configured correctly or incorrectly, a fail or success message will be issued. 

## Instructions to Run
Run the following command: ```ansible-playbook -i inventory.ini assignment1.yaml```

## Screenshot of Successful Execution
![Screenshot showing successful execution.](screenshots/execution.png)