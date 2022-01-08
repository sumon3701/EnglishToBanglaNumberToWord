# EnglishToBanglaNumberToWord

It is use to English number convert to bangla number and Bangla word.

## Requirements

PHP version 7.1 or higher

## Easy Installation

## Install with composer

To install with Composer, simply require the latest version of this package.

```bash
composer require sumon/english-to-bangla-number-to-word
```

## Usage

```php
#namespace
use BNConverter\EnglishToBanglaNumberToWord;

$convert = new EnglishToBanglaNumberToWord;
# In Bangla Word
$convert->numberToWord(100.50);

# একশত দশমিক পাচঁ শূন্য

# In Bangla number
$convert->englishToBangla(100.50);

# ১০০.৫০
```

