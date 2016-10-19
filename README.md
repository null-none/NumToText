# NumToText

Php library for convert convert number to string on russian language.

## Install

```bash
composer require dmitry/num-to-text
```

## Example

```php
$convert = new NumToText();
print $convert->Convert(10);
// десять
print $convert->Convert(122223124120);
// сто двадцать два миллиарда двести двадцать три миллиона сто двадцать четыре тысячи сто двадцать
```

## License

MIT
