Precise-LAMP
============

A basic LAMP stack based on Ubunutu 12.04

Includes the basic LAMP Stack

* GIT,
* Timezone = Berlin/Europe
* VIM
* MySQL-Server
* PHP
* XDebug
* and some more utils

To install the cookbooks you'll have to install [librarian-chef](https://github.com/applicationsonline/librarian-chef).
If you're finished with installing librarian-chef open up your console and point it to the `cd data/vagrant/` folder and type `librarian-chef install`.

When you're done with the those dependencies, install the box specific cookbooks not found on the opscode page by navigating back to the root of the project and typing `git submodule update --init --recursive` which will initialize all submodules.
Please note that you have to have GIT version >= 1.6.5



