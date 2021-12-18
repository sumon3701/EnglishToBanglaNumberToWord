# EnglishToBanglaNumberToWord

It is use to English number convert to bangla number and Bangla word

Requirements
PHP version 7.1 or higher

Easy Installation
Install with composer
To install with Composer, simply require the latest version of this package.
composer require sumon/english-to-bangla-number-to-word

Use

//namespace
use BNConverter\EnglishToBanglaNumberToWord;

$convert = new EnglishToBanglaNumberToWord;

// In Bangla Word
$convert->numberToWord(23423456.78);

// in Bangla number
$convert->englishToBangla(23423456.78);

