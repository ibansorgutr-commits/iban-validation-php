# iban-validation-php
İban Sorgulama , İban Doğrulama, İbandan banka bulma

# IBAN Validation PHP

This repository provides a simple and reliable PHP function to validate IBAN numbers.

## Features
- Supports international IBAN format
- Fast and lightweight
- No external dependencies

## Example Usage

```php
require 'iban.php';

if (validateIBAN('TR260001000297793292015001')) {
    echo 'Valid IBAN';
} else {
    echo 'Invalid IBAN';
}

Live IBAN Validation Tool

You can test IBAN numbers online using this tool:
👉 https://ibansorgu.net
