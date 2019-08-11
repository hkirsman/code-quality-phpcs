# Code Quality PHP_CodeSniffer

This Composer package will provide wrapper for phpcs and phpcbf that prompts for
y/n if phpcs detects it can do automatic fixing. This package does not contain
any Composer dependencies because we don't want to restrict the phpcs versions
in any way.

To install Coder (PHP_CodeSniffer rules with Drupal support) in your project run:

    composer require drupal/coder

If you want to install just the PHP_CodeSniffer in your project run:

    composer require "squizlabs/php_codesniffer=*"
