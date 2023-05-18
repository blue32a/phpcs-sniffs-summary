## Control structures

### PSR2.ControlStructures.ControlStructureSpacing

Checks that control structures have the correct spacing around brackets.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr2controlstructurescontrolstructurespacing)

```php
// Error 👎
if ( $a === 1 ) {
}

foreach ( $items as $item ) {
}

// Fixed 👍
if ($a === 1) {
}

foreach ($items as $item) {
}
```
