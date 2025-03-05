# Ansible

Lo primero es tener instalado Ansible en el servidor (recomiendo Linux)
sudo apt update && sudo apt install ansible

Crear fichero hosts como el que hay en el ejemplo de este repositorio (windows_hosts)

Crear un playbook .yml o .yaml y ejecutarlo
ansible-playbook -i windows_hosts(o el fichero host que quieras) test.yml(o el fichero que quieras)
