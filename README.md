# U232 to UNIT3D

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-github-actions]][link-github-actions]
[![Style CI][ico-styleci]][link-styleci]
[![Total Downloads][ico-downloads]][link-downloads]

An artisan package to import a [U-232] database into [UNIT3D].

## Install

Via Composer

```bash
$ composer require pxgamer/u232-to-unit3d --dev
```

To install, just:
- Require this package from your [UNIT3D][unit3d] install.
- Add an empty `imports` entry to your database config.

## Usage

For instructions on usage, run:

```bash
php artisan unit3d:from-u232 --help
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

```bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Credits

- [Owen Voke][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[unit3d]: https://github.com/unit3d/unit3d
[u-232]: https://github.com/bigjoos/u-232-v5
[providers]: https://laravel.com/docs/master/providers#registering-providers

[ico-version]: https://img.shields.io/packagist/v/pxgamer/u232-to-unit3d.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-github-actions]: https://img.shields.io/github/workflow/status/HDInnovations/u232-to-unit3d/Tests.svg?style=flat-square
[ico-styleci]: https://styleci.io/repos/114423312/shield
[ico-downloads]: https://img.shields.io/packagist/dt/pxgamer/u232-to-unit3d.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/pxgamer/u232-to-unit3d
[link-github-actions]: https://github.com/HDInnovations/u232-to-unit3d/actions
[link-styleci]: https://styleci.io/repos/114423312
[link-downloads]: https://packagist.org/packages/pxgamer/u232-to-unit3d
[link-author]: https://github.com/owenvoke
[link-contributors]: ../../contributors
