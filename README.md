# nginx

Плейбук устанавливает на хост docker, docker-compose, firewalld и настраивает файервол. Роль ansible-nginx запускает контейнер с nginx. Увидеть результат можно с помощью следующей команды:

```
curl 46.148.239.122:8080
```

Плейбук запускается командой:

```
ansible-playbook nginx.yml -D -b -u root -i inventory.yml --ask-pass
```
После запуска необходимо ввести рутовый пароль.