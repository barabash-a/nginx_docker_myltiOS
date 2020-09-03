# nginx_docker_myltiOS
Install nginx and docker,create nginx.conf,script cold docker restart and add task crontab, configure ufw. OS - Ubuntu, Centos
ansible version 2.9
start playbook:
1. add ip - hosts
2. ansible-playbook -i hosts WebServerMultiOS.yml
3. enter host,port,name domain, name nginx.conf
