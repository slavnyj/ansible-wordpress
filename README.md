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
Для локальной установки WordPress, выполняем
```
ansible-playbook site.yaml
```

На сервере будет установлен:
- WordPress (последняя версия)
- UFW
- MariaDB (последняя версия)
- NGINX (последняя версия)
- Postfix
- PHP-FPM 7.4
- phpMyAdmin
- Redis
- SFTP
