# PSR-7 Bridge for Icicle

Bridges the asynchronous HTTP messages and streams of Icicle's [HTTP component](https://github.com/icicleio/http) to [PSR-7](http://www.php-fig.org/psr/psr-7/) compatible interface. Use with caution and only in cases where blocking is acceptable, as reading or writing from a synchronous stream can block the entire process.

## Installation

The recommended way to install is with the Composer package manager. (See the Composer installation guide for information on installing and using Composer.)

Run the following command to use this library in your project:

```
composer require icicleio/psr7-bridge
```

You can also manually edit composer.json to add this library as a project requirement.

```
// composer.json
{
    "require": {
        "icicleio/psr7-bridge": "dev-master"
    }
}
```

[![@icicleio on Twitter](https://img.shields.io/badge/twitter-%40icicleio-5189c7.svg?style=flat-square)](https://twitter.com/icicleio)
[![Build Status](https://img.shields.io/travis/icicleio/psr7-bridge/master.svg?style=flat-square)](https://travis-ci.org/icicleio/psr7-bridge)
[![Coverage Status](https://img.shields.io/coveralls/icicleio/psr7-bridge.svg?style=flat-square)](https://coveralls.io/r/icicleio/psr7-bridge)
[![Semantic Version](https://img.shields.io/github/release/icicleio/psr7-bridge.svg?style=flat-square)](http://semver.org)
[![MIT License](https://img.shields.io/packagist/l/icicleio/psr7-bridge.svg?style=flat-square)](LICENSE)

Currently under development.
