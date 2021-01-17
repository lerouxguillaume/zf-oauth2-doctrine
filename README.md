OAuth2 Doctrine ORM Adapter for Apigility
=========================================

> This is a Fork of https://github.com/API-Skeletons/zf-oauth2-doctrine

[![Build Status](https://travis-ci.org/samsonasik/zf-oauth2-doctrine.svg)](https://travis-ci.org/samsonasik/zf-oauth2-doctrine)
[![Documentation Status](https://readthedocs.org/projects/doctrine-in-apigility-docs/badge/?version=latest)](http://doctrine-in-apigility-docs.readthedocs.io/en/latest/zf-oauth2-doctrine/index.html)
[![Gitter](https://badges.gitter.im/samsonasik/open-source.svg)](https://gitter.im/samsonasik/open-source)
[![Patreon](https://img.shields.io/badge/patreon-donate-yellow.svg)](https://www.patreon.com/apiskeletons)
[![Total Downloads](https://poser.pugx.org/samsonasik/zf-oauth2-doctrine/downloads)](https://packagist.org/packages/samsonasik/zf-oauth2-doctrine)

This provides a Doctrine adapter for [laminas-api-tools/api-tools-mvc-auth](https://github.com/laminas-api-tools/api-tools-mvc-auth) and [laminas-api-tools/api-tools-oauth2](https://github.com/laminas-api-tools/api-tools-oauth2) and entity definitions for all aspects of OAuth2 including Authorization Code, Access Tokens, Refresh Tokens, JWT & JTI, and Scopes.

Versions
--------

* 1.x series is for PHP 5.5 to 7.0.
* 2.x series is for PHP 7.1 onward.
* 3.x series is for PHP 7.1 onward and uses bigint instead of integer, scope fixture, and bcrypt cost of 10.
* 4.x series is for PHP 7.3|~8.0 with laminas support.

![Entity Relationship Diagram](https://raw.githubusercontent.com/samsonasik/zf-oauth2-doctrine/master/media/oauth2-doctrine-erd.png)
Entity Relationship Diagram created with [Skipper](https://skipper18.com)

[Read The Documentation](http://doctrine-in-apigility-docs.readthedocs.io/en/latest/zf-oauth2-doctrine/index.html)
======
