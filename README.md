Symfony 2.1 Composer Edition
============================

## Introduction

Symfony 2.1 Composer Edition is managed by [Composer](http://getcomposer.org/)
and [Packagist](http://packagist.org/) thanks to the great work of [@Seldaek](https://github.com/Seldaek) and others.

We give lots of credits to the work of KnpLabs [symfony with composer](https://github.com/KnpLabs/symfony-with-composer).

### What's in it ?

You'll find some pre configured stuff like :

* Twig as the template engine
* Monolog as the default logger
* Swiftmailer as the email sender
* A lightweight AcmeDemoBundle on dev/test environment
* Buzz & BuzzBundle, a lightweight HTTP client

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
Having troubles ? [Read the doc](http://symfony.com/doc/current/book/installation.html#configuration-and-setup)

### Configure and install dependencies with composer

Setup the project dependencies in file composer.json located on root directory.
[Read the doc](https://github.com/composer/composer)

Then get composer


``` bash
$ curl -s http://getcomposer.org/installer | php
```

When done, let composer download and install all your dependencies by executing the following command:

``` bash
$ php composer.phar install
```

You can also update the dependencies by running the previous command with ```update``` option instead of ```install```.

### See it live

Remembering the first step, as you extracted the archive in your local web dir, you can now hit your favorite browser at :

```
http://localhost/Symfony/web/app_dev.php/demo
```

Congrats !
Now you can customize this distribution with ```composer.json``` : don't forget to read more about [Packagist](http://packagist.org/).