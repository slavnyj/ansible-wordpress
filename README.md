# ansible-wordpress


На хосте c Ubuntu должен быть установлен Ansible.
```
sudo apt update
sudo apt install ansible
```
Клонируем репозиторий
```
git clone https://github.com/slavnyj/ansible-wordpress.git
cd ansible-wordpress
```
Для локальной утсановки WordPress, выполняем
```
ansible-playbook site.yaml
```
