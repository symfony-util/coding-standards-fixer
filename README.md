# coding-standards-fixer
PHP Coding Standards Fixer Configuration from symfony/demo as a function of fileHeaderComment

[![PHPPackages Rank](http://phppackages.org/p/symfony-util/coding-standards-fixer/badge/rank.svg)](http://phppackages.org/p/symfony-util/coding-standards-fixer)
[![Maintainability](https://api.codeclimate.com/v1/badges/c6954898e6d8da282d08/maintainability)](https://codeclimate.com/github/symfony-util/coding-standards-fixer/maintainability)
[![Build Status](https://travis-ci.org/symfony-util/coding-standards-fixer.svg?branch=master)](https://travis-ci.org/symfony-util/coding-standards-fixer)

* See RuleSet: https://github.com/FriendsOfPHP/PHP-CS-Fixer/blob/master/src/RuleSet.php

## TODO

* Implement the proposer ruleset as an array constant http://php.net/manual/en/language.constants.syntax.php
  * array constant requires PHP 5.6 (no idea how to implement it before 5.6, better just do not try to find more solutions)
  ```
  php > print_r(array_merge(null, array('dog', 'cat', 'bird')));
  PHP Warning:  array_merge(): Argument #1 is not an array in php shell code on line 1
  ```
