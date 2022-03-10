# Perform unit conversions in PHP

[![Latest Version on Packagist](https://img.shields.io/packagist/v/mnaderian/unit-conversions.svg?style=flat-square)](https://packagist.org/packages/mnaderian/unit-conversions)
[![Tests](https://github.com/mnaderian/unit-conversions/actions/workflows/run-tests.yml/badge.svg?branch=main)](https://github.com/mnaderian/unit-conversions/actions/workflows/run-tests.yml)
[![Total Downloads](https://img.shields.io/packagist/dt/mnaderian/unit-conversions.svg?style=flat-square)](https://packagist.org/packages/mnaderian/unit-conversions)

This package can perform various unit conversions. Right now, only kg to lbs is supported.

Here's how to use it:

```php
use Mnaderian\UnitConversions\Weight;

Weight::fromKilograms(100)->toLbs(); // returns 220.4623;
```

## Installation

You can install the package via composer:

```bash
composer require mnaderian/unit-conversions
```

## Usage

```php
$skeleton = new Mnaderian\UnitConversions();
echo $skeleton->echoPhrase('Hello, Mnaderian!');
```

## Testing

```bash
composer test
```

## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Security Vulnerabilities

Please review [our security policy](../../security/policy) on how to report security vulnerabilities.

## Credits

- [Mahdi Naderian](https://github.com/mnaderian)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
