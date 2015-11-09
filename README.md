# codekata-php
Vagrant setup by [https://puphpet.com/](https://puphpet.com/)

## What's included?
- Ubuntu Trusty 14.04 LTS x64
- PHP 5.6
- PHP modules: cli, intl, mcrypt & curl
- Composer
- Xdebug
- Ruby 1.9.3
- Python 2.7

## How to spin up the server
- clone / download the repository
- open your terminal and navigate to the repository location, example: `cd ~/Sites/codekata-php`
- just run `vagrant up` and PUPHPET will set up everything for you
- after the provisioning is done, ssh into the VM using `vagrant ssh`
- your local repository directory is shared with the VM: `/vagrant` & `/var/www`
- dependencies are handled automatically by Composer every time you start the VM

## Happy Coding!
## ToDo
- add descriptions for as many code katas as possible
