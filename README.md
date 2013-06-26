# Doctrine Bundle

Doctrine DBAL & ORM Bundle for the EasyFw Framework.

Because EasyFw 2 does not want to force or suggest a specific persistence solutions on the users
this bundle was removed from the core of the EasyFw 2 framework. Doctrine2 will still be a major player
in the EasyFw world and the bundle is maintained by developers in the Doctrine and EasyFw communities.

    IMPORTANT: This bundle is developed for EasyFw 2.1 and up. For EasyFw 2.0 applications the DoctrineBundle
    is still shipped with the core EasyFw repository.

Build Status: [![Build Status](https://secure.travis-ci.org/doctrine/DoctrineBundle.png?branch=master)](http://travis-ci.org/doctrine/DoctrineBundle)

## What is Doctrine?

The Doctrine Project is the home of a selected set of PHP libraries primarily focused on providing persistence
services and related functionality. Its prize projects are a Object Relational Mapper and the Database Abstraction
Layer it is built on top of. You can read more about the projects below or view a list of all projects.

Object relational mapper (ORM) for PHP that sits on top of a powerful database abstraction layer (DBAL).
One of its key features is the option to write database queries in a proprietary object oriented SQL dialect
called Doctrine Query Language (DQL), inspired by Hibernates HQL. This provides developers with a powerful
alternative to SQL that maintains flexibility without requiring unnecessary code duplication.

DBAL is a powerful database abstraction layer with many features for database schema introspection,
schema management and PDO abstraction.

## Installation

### 1. Old deps and bin/vendors way

Add the following snippets to "deps" files:

    [doctrine-dbal]
        git=http://github.com/doctrine/dbal.git

    [doctrine-orm]
        git=http://github.com/doctrine/doctrine2.git

    [DoctrineBundle]
        git=http://github.com/doctrine/DoctrineBundle.git
        target=/bundles/Doctrine/Bundle/DoctrineBundle

### 2. Composer

Add the following dependencies to your projects composer.json file:

    "require": {
        # ..
        "easyframework/doctrine-bundle": ">=2.1"
        # ..
    }

## Documentation

See the Resources/docs folder more a full documentation.
