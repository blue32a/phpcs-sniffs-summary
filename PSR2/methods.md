## Methods

### PSR2.Methods.FunctionCallSignature

Checks that the function call format is correct.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr2methodsfunctioncallsignature)

```php
// Error 👎
somefunction( $foo, $bar );

somefunction2(
  $foo,
    $bar);

// Fixed 👍
somefunction($foo, $bar);

somefunction2(
    $foo,
    $bar
);
```
