Symfony 2.1 Composer Edition
============================

## Introduction

Symfony 2.1 Composer Edition is managed by [Composer](http://getcomposer.org/)
and [Packagist](http://packagist.org/) thanks to the great work of [@Seldaek](https://github.com/Seldaek) and others.

We give lot of credits to the work of KnpLabs [symfony with composer](https://github.com/KnpLabs/symfony-with-composer).

### What's in it ?

You'll find some pre configured stuff like :

* Twig as the template engine
* Swiftmailer as the email sender
* MongoDB as the storage with Doctrine as the ODM
* Annotations but not for Doctrine
* A lightweight AcmeDemoBundle on dev/test environment

Interested ? Just go through this steps in order to get started :

1. Download the Symfony 2.1 Composer Edition
2. Check Symfony requirements
3. Install vendors
4. See it live in your browser

## Installation process

### Download the Composer Edition

Download archive from [here](https://github.com/Plemi/symfony-composer-edition/zipball/master).

### Check Symfony requirements

Once you've downloaded the composer edition, extract in your local web dir and go to the extracted folder. Then run this command :

``` bash
$ php app/check.php
```

We suggest fixing any issues or Symfony recommandations before moving on.

### Install vendors

Just like the standard version of Symfony, you just have to run the same commands that will install/update vendors, update bootstrap file, install assets and clear your cache.

``` bash
$ php bin/vendors install
```

In order to update dependencies, run the previous command with ```update``` option.

### See it live

Remembering the first step, as you extracted the archive in your local web dir, you can now hit your favorite browser at :

```
http://localhost/Symfony/web/app_dev.php/demo
```

Congrats !
Now you can customize this distribution with ```composer.json``` : don't forget to read more about [Packagist](http://packagist.org/).