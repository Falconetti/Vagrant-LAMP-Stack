# Vagrant LAMP stack
A dead-simple LAMP stack without any bells and whistles for your basic Linux/Apache/MySQL/PHP install.

Fork this and add additional software and configuration that suits the needs of your project.

## Requirements:
* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)
* [vagrant-hostmaster](https://github.com/mosaicxm/vagrant-hostmaster)

## Installation
Clone this repository

    $ git clone git@github.com:MiniCodeMonkey/Vagrant-LAMP-Stack.git
    $ cd Vagrant-LAMP-Stack
    $ git submodule update --init

Place your website in the *public_html* folder

## Usage
Start the VM

	$ vagrant up

You can now access your project at [http://server.dev](http://server.dev)

![Screenshot of up-and-running server](http://i.imgur.com/TP1i9Zd.png)

## Installed software:
* Apache 2
* MySQL
* PHP 5.4 (with mysql, curl, mcrypt, memcached, gd)
* memcached
* vim, git, screen, curl, composer

## Default credentials
### MySQL
* Username: root
* Password: root
* Host: localhost
* Port: 3306

**Note:** Remote MySQL access is enabled by default, so you can access the MySQL database using your favorite MySQL client with the above credentials (and using e.g. *server.dev* as hostname).

### Memcached
* Port: 11211



Einrichtung Lamp-Vagrant
- Es wird folgendes Repo genutzt: 
https://github.com/MiniCodeMonkey/Vagrant-LAMP-Stack

Eine Anleitung befindet sich im Repo.


Fork mit Erweiterungen herunterladen:
$ git clone git@github.com:Falconetti/Vagrant-LAMP-Stack --recursive



Vagrant installieren:
http://downloads.vagrantup.com/tags/v1.2.2

Virtual Box installieren:
 4.2.12



Vagrant starten:
$ cd Vagrant-LAMP-Stack
Vagrant hostmaster installieren
$ vagrant plugin install vagrant-hostmanager
$ vagrant up

Evtl. startet der Server nicht durch. Es hilft den Server in vmware zu löschen und dann noch einmal init zu starten.

Im Anschluss ist der Server verfügbar unter:
http://server.dev


