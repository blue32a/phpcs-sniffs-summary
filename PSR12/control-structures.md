## Control structures

### PSR12.ControlStructures.BooleanOperatorPlacement

Checks that control structures have boolean operators in the correct place.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr12controlstructuresbooleanoperatorplacement)

```php
// Error 👎
if (
    $a > 0 &&
    $a <= 10
    || $b == 1
) {
}

// Fixed 👍
if (
    $a > 0
    && $a <= 10
    || $b == 1
) {
}
```
