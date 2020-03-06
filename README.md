# Flagship PHP SDK
> Non-official ABTasty Flagship.io SDK for PHP

[![Latest Stable Version](https://img.shields.io/packagist/v/wcomnisky/flagship-php-sdk.svg?style=flat-square)](https://packagist.org/packages/wcomnisky/flagship-php-sdk)

![Branch develop](https://img.shields.io/badge/branch-develop-brightgreen.svg?style=flat-square)
[![Build Status](https://img.shields.io/travis/wcomnisky/flagship-php-sdk/develop.svg?style=flat-square)](https://travis-ci.org/wcomnisky/flagship-php-sdk)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/wcomnisky/flagship-php-sdk/develop.svg?style=flat-square)](https://scrutinizer-ci.com/g/wcomnisky/flagship-php-sdk/?branch=develop)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/wcomnisky/flagship-php-sdk/develop.svg?style=flat-square)](https://scrutinizer-ci.com/g/wcomnisky/flagship-php-sdk/?branch=develop)

* Flagship.io official documentation:  
  http://developers.flagship.io/api/v1/

## Installation

Package is available on [Packagist](https://packagist.org/packages/wcomnisky/flagship-php-sdk),
you can install it using [Composer](https://getcomposer.org).

```shell
composer require wcomnisky/flagship-php-sdk
```

### Requirements

* PHP 7.3 or higher
  * cURL extension recommended

## List of implemented features

**Run all Campaigns assignment**

Documentation: http://developers.flagship.io/api/v1/#run-all-campaigns-assignment

* `[x]` POST HTTP Request
* `[ ]` GET HTTP Request
* `[ ]` Query Parameter `format_response`
* `[x]` Query Parameter `trigger_hit`
* `[x]` Query Parameter `decision_group`

**Run a single Campaign assignment**

Documentation: http://developers.flagship.io/api/v1/#run-a-single-campaign-assignment

* `[x]` POST HTTP Request
* `[ ]` GET HTTP Request
* `[ ]` Query Parameter `mode` (does it applies here too? possibly..)
* `[ ]` Query Parameter `trigger_hit`
* `[ ]` Query Parameter `decision_group`
