# Laravel package for formatting currency at blade view

![Downloads](https://img.shields.io/packagist/dt/wannabestart/currency-blade)

This package can help you to format currency at blade directives.

## Getting Started

### Install

Run the following command:

```bash
composer require wannabestart/currency-blade
```

## Usage

### Blade Directives

General syntax
```php
@formatcurrency('3CODE',MONEYVALUE)
```

Example using at Blade Directives
```php
@formatcurrency('USD', 25000) // $25,000.00 
@formatcurrency('IDR', 25000) // Rp25.000,00
@formatcurrency('', 25000) // If code NULL it will return its value
```
You can check your 3 code of currency [here](https://www.iban.com/currency-codes)

## Changelog

Please see [Releases](../../releases) for more information what has changed recently.

## Contributing

Pull requests are more than welcome. You must follow the PSR coding standards.

## Security

If you discover any security related issues, You can issued on this repository.

## Credits

- [Kharansyah](https://github.com/rans0)
- [All Contributors](https://github.com/wannabestart)

## License

The MIT License (MIT).

## Still improving to update new feature 🔥
