<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://github.com/yiisoft.png" height="100px">
    </a>
    <h1 align="center">Yii HTTP</h1>
    <br>
</p>

The package provides handy HTTP utility such as method constants.

[![Latest Stable Version](https://poser.pugx.org/yiisoft/http/v/stable.png)](https://packagist.org/packages/yiisoft/http)
[![Total Downloads](https://poser.pugx.org/yiisoft/http/downloads.png)](https://packagist.org/packages/yiisoft/http)
[![Build Status](https://travis-ci.com/yiisoft/http.svg?branch=master)](https://travis-ci.com/yiisoft/http)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/yiisoft/http/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/http/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/yiisoft/http/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/yiisoft/http/?branch=master)

## Method constants

Individual HTTP methods could be referenced as

```php
use Yiisoft\Http\Method;

Method::GET;
Method::POST;
Method::PUT;
Method::DELETE;
Method::PATCH;
Method::HEAD;
Method::OPTIONS;
```

To have a list of these, use:

```php
use Yiisoft\Http\Method;

Method::ANY;
```

## HTTP status codes

Status codes could be referenced by name as:

```php
use Yiisoft\Http\Status;

Status::NOT_FOUND;
```

Status text could be obtained as the following:

```php
use Yiisoft\Http\Status;

Status::TEXTS[Status::NOT_FOUND];
```
