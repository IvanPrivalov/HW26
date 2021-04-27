# Динамический веб контент

## Задание

Роль для настройки веб сервера Варианты стенда nginx + php-fpm (laravel/wordpress) + python (flask/django) + js(react/angular) nginx + java (tomcat/jetty/netty) + go + ruby можно свои комбинации

Реализации на выбор

- на хостовой системе через конфиги в /etc
- деплой через docker-compose

Для усложнения можно попросить проекты у коллег с курсов по разработке

К сдаче примается vagrant стэнд с проброшенными на локалхост портами каждый порт на свой сайт через нжинкс

## Выполнение ДЗ

Копируем файлы в каталог и запускаем Vagrantfile:

```shell
vagrant up
```

### Ansible-playbook разворачивает комбинацию nginx + php-fpm (laravel) + python (django) + js(react)

### Проверка:

1. Проверка:

php-fpm/laravel - http://192.168.10.10:10001/

![image 1](https://github.com/IvanPrivalov/HW26/blob/master/screens/10001.png)

http://192.168.10.10:10001/homework

![image 2](https://github.com/IvanPrivalov/HW26/blob/master/screens/10001hw.png)

uwsgi/django - http://192.168.10.10:10002/

![image 3](https://github.com/IvanPrivalov/HW26/blob/master/screens/10002.png)

nodejs/reactjs - http://192.168.10.10:10003/

![image 4](https://github.com/IvanPrivalov/HW26/blob/master/screens/10003.png)



