# CakePHP Tags Plugin

[![Build Status](https://img.shields.io/travis/dereuromark/cakephp-tags/master.svg?style=flat-square)](https://travis-ci.org/dereuromark/cakephp-tags)
[![Coverage Status](https://img.shields.io/codecov/c/github/dereuromark/cakephp-tags/master.svg)](https://codecov.io/github/dereuromark/cakephp-tags?branch=master)
[![Latest Stable Version](https://poser.pugx.org/dereuromark/cakephp-tags/v/stable.svg)](https://packagist.org/packages/dereuromark/cakephp-tags)
[![Total Downloads](https://img.shields.io/packagist/dt/dereuromark/cakephp-tags.svg?style=flat-square)](https://packagist.org/packages/dereuromark/cakephp-tags)
[![Minimum PHP Version](http://img.shields.io/badge/php-%3E%3D%205.6-8892BF.svg)](https://php.net/)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://packagist.org/packages/dereuromark/cakephp-tags)

Make tagging of entities a piece of cake.

This branch is for CakePHP 3.6+.

## Install

Using Composer:

```
composer require dereuromark/cakephp-tags
```

You then need to load the plugin. In `boostrap.php`, something like:

```php
use Cake\Core\Plugin:

Plugin::load('Tags');
```

Also don't forget to run migration (e.g. using Migrations plugin):
```
bin/cake migrations migrate -p Tags
```

## Demo
See Sandbox @ https://sandbox.dereuromark.de/sandbox/tags

## Documentation

For documentation, as well as tutorials, see the [docs](docs/) directory of this repository.

## Support

For bugs and feature requests, please use the [issues](https://github.com/dereuromark/cakephp-tags/issues) section of this repository.
