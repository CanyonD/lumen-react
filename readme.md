Lumen (Laravel Micro Framework) + ReactJS + AdminLTE + Webpack Boilerplate

## Prerequisites

- PHP >= 5.6.4
- OpenSSL PHP Extension
- PDO PHP Extension
- Mbstring PHP Extension
- [NodeJs](https://nodejs.org/en/)
- [Composer](https://getcomposer.org/download/) - Package manager for PHP
- [NPM](https://npmjs.org/) - Node package manager


## Installation
On the command prompt run the following commands:
```
 $ git clone https://github.com/Bikranshu/lumen-react.git
 $ cd lumen-react
 $ composer install
 $ npm install
 $ cp .env.example .env
 $ php artisan jwt:secret
 $ php artisan migrate
 $ php artisan db:seed
 $ php -S 192.168.0.171:8080 -t public/
 $ npm run watch
```
Credential:
- username: admin@admin.com
- password: 1234

## USEFUL LINK
- Lumen [https://lumen.laravel.com](https://lumen.laravel.com/)
- dingo/api [https://github.com/dingo/api](https://github.com/dingo/api)
- json-web-token(jwt) [https://github.com/tymondesigns/jwt-auth](https://github.com/tymondesigns/jwt-auth)
- transformer [fractal](http://fractal.thephpleague.com/)
- apidoc [apidocjs](http://apidocjs.com/)
- debug rest api [postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop?hl=en)
- api doc [http://lumen.lyyw.info/apidoc](http://lumen.lyyw.info/apidoc)
- JavaScript library for building user interfaces - [React](https://facebook.github.io/react/)
- Predictable state container - [Redux](http://redux.js.org/)
- Promise based HTTP client - [Axios](https://github.com/mzabriskie/axios)

## MySQL on Centos7
$ yum install mariadb-server mariadb
$ systemctl start mariadb
$ sudo mysql_secure_installation
$ mysql -u root -p
$ CREATE DATABASE `homestead`;
$ CREATE USER 'homestead' IDENTIFIED BY 'secret';
$ GRANT USAGE ON *.* TO 'homestead'@localhost IDENTIFIED BY 'secret';
$ GRANT ALL privileges ON *.* TO 'homestead'@'%';
$ FLUSH PRIVILEGES;
$ rpm -Uhv https://rpms.southbridge.ru/rhel7/php-7.2/x86_64/php-mysqlnd-7.2.3-2.el7.remi.x86_64.rpm