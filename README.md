Sublime Text PHP Grammar
========================

PHP [~5.5](http://semver.org) syntax definition.

## Features

- Bug fixes
- Improved indentation
- Updated support for PHP ~5.5 builtin classes, functions, and constants

## Changelog

See [CHANGELOG](CHANGELOG.md).

## Contribute

See [CONTRIBUTING](CONTRIBUTING.md).

## Installation

1. Disable the `PHP` package bundled with Sublime Text

   Add `PHP` to the list of ignored packages in the User Settings.

   Go to `Preferences > Settings - User` and add the following:

   ```json
   "ignored_packages":
   [
     "PHP"
   ]
   ```

2. Clone into the `Packages` directory

   e.g. Ubuntu

   ```sh
   cd ~/.config/sublime-text-3/Packages
   git clone https://github.com/gerardroche/sublime-php-grammar.git
   ```

## Other PHP packages

* [PHP Grammar](https://github.com/gerardroche/sublime-php-grammar)
* [PHP Completions](https://github.com/gerardroche/sublime-phpck)
* [PHP Snippets](https://github.com/gerardroche/sublime-php-snippets)
* [PHPUnit Completions](https://github.com/gerardroche/sublime-phpunitck)
* [PHPUnit Snippets](https://github.com/gerardroche/sublime-phpunit-snippets)
