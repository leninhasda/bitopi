# bitopi
Dockerized environment for developing PHP applications

> Inspired and customized version of [Vessel](https://github.com/shipping-docker/vessel)

## What's included?
- Ubuntu 16.04
- Nginx
- PHP 7.2-fpm
  - modules: pgsql, sqlite3, gd, curl, memcached, imap, mysql, mbstring, xml, zip, bcmath, soap, intl, xdebug, msgpack, igbinary

## Install
Just download as zip or git clone command in terminal:
```
git clone https://github.com/leninhasda/bitopi.git
```
Then copy `docker` folder, `bitopi` and `docker-compose.yml` file in your project directory. Finally run the following command in your project path to initialize:
```
sudo bash bitopi init
```

## How to use
