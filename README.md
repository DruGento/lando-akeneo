# Lando configuration to run Akeneo project

## 📄 Description

A simple and quick way to get Akeneo up and running locally with Lando


## 🛠 Installation

* Install [Lando](https://docs.lando.dev)
* Clone this repository
* `cd` to cloned folder
* Run `lando start` to install lando services
* Run `lando akeneo-install` - this command will clone Akeneo project and 
run `NO_DOCKER=true make dev`


## 🎮 Usage

This config uses Lando recipe for Symfony. Documentation is available [here](https://docs.lando.dev/symfony/)

The recipe comes with preconfigured commands to run composer, console and other:

* `lando composer`          Runs composer commands
* `lando console`           Runs console commands
* `lando db-export [file]`  Exports database from a service into a file
* `lando db-import <file>`  Imports a dump file into database service
* `lando mysql`             Drops into a MySQL shell on a database service
* `lando php`               Runs php commands


## ⚖️ License

Generously distributed under the _[MIT](https://opensource.org/licenses/MIT)_
