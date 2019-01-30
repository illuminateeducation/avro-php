What the Avro PHP library is
============================

A library for using [Avro](http://avro.apache.org/) with PHP.

This is a fork of wikimedia/avro-php. AvroDataIoReader is only able to read avro files into memory and the class isn't easily extensible. This fork will add accessors so that iterative reading is possible.

Requirements
------------
 * PHP 5.5.9+
 * On 32-bit platforms, the [GMP PHP extension](http://php.net/gmp)
 * For testing, [PHPUnit](http://www.phpunit.de/)

Both GMP and PHPUnit are often available via package management
systems as `php5-gmp` and `phpunit`, respectively.

Getting started
---------------
```
$ composer require illuminateeducation/avro-php
```

History
-------
Extracted from https://github.com/apache/avro using `git subtree`.
