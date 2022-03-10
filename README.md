![](https://github.com/VKCOM/ktest/blob/master/docs/readme_header.png)

## Overview

`ktest-script` is a binary release of [ktest](https://github.com/VKCOM/ktest) for composer. 

`ktest` is a tool that makes [kphp](https://github.com/VKCOM/kphp/) programs easier to test.

## Installation

```bash
$ composer require --dev vkcom/ktest-script
```

## Usage

```bash
# Running tests with KPHP:
$ ./vendor/bin/ktest phpunit ./tests

# Running benchmarks with KPHP
$ ./vendor/bin/ktest bench ./benchmarks

# Running benchmarks with PHP
$ ./vendor/bin/ktest bench-php ./benchmarks
```

For more usage information, see [ktest](https://github.com/VKCOM/ktest) docs.
