# Menu and sidebar management package for Laravel

[![Version](https://poser.pugx.org/akaunting/menu/v/stable.svg)](https://github.com/akaunting/menu/releases)
![Downloads](https://poser.pugx.org/akaunting/menu/d/total.svg)
![Build Status](https://travis-ci.com/akaunting/menu.svg)
[![StyleCI](https://styleci.io/repos/180763610/shield?style=flat&branch=master)](https://styleci.io/repos/180763610)
[![Quality](https://scrutinizer-ci.com/g/akaunting/menu/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/akaunting/menu)
[![License](https://poser.pugx.org/akaunting/menu/license.svg)](LICENSE.md)

This package intends to create and manage menus and sidebars for your Laravel app. It ships with ready-to-go presenters and you can create your own ones.

## Getting Started

### 1. Install

Run the following command:

```bash
composer require akaunting/menu
```

### 2. Register

Service provider and facade will be registered automatically. If you want to register them manually in `config/app.php`:

```php
Akaunting\Menu\Facade::class,
Akaunting\Menu\Provider::class,
```

### 3. Publish

Publish config file.

```bash
php artisan vendor:publish --tag=menu
```

### 4. Configure

You can change the configuration from `config/menu.php` file

## Usage

Check out the [wiki](../../wiki) about the usage and further documentation.

## Changelog

Please see [Releases](../../releases) for more information what has changed recently.

## Contributing

Pull requests are more than welcome. You must follow the PSR coding standards.

## Credits

- [Denis Duliçi](https://github.com/denisdulici)
- [All Contributors](../../contributors)

## License

The MIT License (MIT). Please see [LICENSE](LICENSE.md) for more information.
