# Dev environment (Parallel Desktop)

### What's in the box?!
- Debian Wheezy 7.5 x64
- PHP 5.6 
- NFS sync folder
- vim, htop, memcached
- NGINX with 2 hosts
- MariaDB, PostgreSQL, SQLite, Redis, MongoDB
- MailCatcher
- RabbitMQ
- Elastic Search


### Installation
1. git clone git@github.com:dutchakdev/devenv.git
2. install vagrant https://www.vagrantup.com/downloads.html
3. install Parallel Desktop (if not installed)
4. Run $ vagrant up and go grab a coffee ☕️


### Problems? 

if you have:
```
The provider 'parallels' could not be found, but was requested to
back the machine 'default'. Please use a provider that exists.
```

you want run:
```
$  vagrant plugin install vagrant-parallels
```