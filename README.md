  Zend Framework 2 DDD Persistence Module (Doctrine\ORM)
========================================================

## Introduction

**ZfPersistenceDoctrineORM** is a Zend Framework 2 module providing the basics for persistence using Doctrine\ORM
trying to follow [DDD principles](http://domaindrivendesign.org/books/#DDD).

## Requirements

* Zend Framework 2
* Doctrine 2
* [ZfPersistenceBase](https://github.com/goten4/ZfPersistenceBase)

## Installation

Via composer or simply clone this project into your `./vendor/` directory and enable it in your
`./config/application.config.php` file.

Provided Classes and Interfaces
-------------------------------

* `ZfPersistenceDoctrineORM\Infrastructure\DoctrineORMRepository` - Doctrine\ORM Repository implementation.
* `ZfPersistenceDoctrineORM\Infrastructure\DoctrineORMRepositoryFactory` - Factory for creating DoctrineORMRepository

## See also

* [ZfPersistenceBase](https://github.com/goten4/ZfPersistenceBase)
* [ZfPersistenceZendDb](https://github.com/goten4/ZfPersistenceZendDb)
