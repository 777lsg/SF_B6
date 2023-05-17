# SF_B6
Управление конфигурациями (Ansible, Puppet)
1. На машинах группы app выполняется установка и запуск Docker;
- deploy_docker
- play_docker.yml

2. На машинах группы database выполняется установка и запуск postgresql-server (версия и data-директория должны быть переменными, задающимися в inventory).
- deploy_psql
- play_psql.yml