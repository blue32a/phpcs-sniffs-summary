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

### PSR2.ControlStructures.ElseIfDeclaration

Verifies that there are no else if statements (elseif should be used instead).

```php
// Error 👎
if ($a === 1) {
} else if ($a === 2) {
}

// Fixed 👍
if ($a === 1) {
} elseif ($a === 2) {
}
```
