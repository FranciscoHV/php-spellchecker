# php-spellchecker

Spell check html files

It's working with :

*   [LanguageTool](https://www.languagetool.org/)
*   [Guzzle](http://docs.guzzlephp.org)
*   [Symfony Finder Component](http://symfony.com/doc/2.3/components/finder.html)
*   [Glicer Simply-html Component](https://github.com/emmanuelroecker/php-simply-html)

## Installation

This library can be found on [Packagist](https://packagist.org/packages/glicer/spell-checker).

The recommended way to install is through [composer](http://getcomposer.org).

Edit your `composer.json` and add:

```json
{
    "require": {
       "glicer/spell-checker": "dev-master"
    }
}
```

And install dependencies:

```bash
php composer.phar install
```

## How to spell check html files ?

```php
<?php
    require 'vendor/autoload.php';

    use GlSpellChecker\GlSpellChecker;
```

## Running Tests

Launch from command line :

```console
vendor\bin\phpunit
```

## Contact

Authors : Emmanuel ROECKER & Rym BOUCHAGOUR

[Web Development Blog - http://dev.glicer.com](http://dev.glicer.com)