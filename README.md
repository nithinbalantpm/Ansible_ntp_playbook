Steps to Execute This ansible playbook
1. Copy ntp_playbook.yml file to /etc/ansible directory
2. Create folder named templates in /etc/ansible and put our ntp configruation file ntp.conf inside in that directory
3. cd /etc/ansible
4. Then run the command  ansible-playbook ntp_playbook.yml in your favorite terminal.

Note: 

 webservers ansible host group should configured in /etc/ansible/hosts file
