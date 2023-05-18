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

### PSR2.ControlStructures.SwitchDeclaration

Ensures all switch statements are defined correctly.

```php
// Error 👎
switch ($expr) {
    case   1:
        echo 'First case';
        break;
    Case 2:
        echo 'Second case';
        break;
    Default:
        echo 'Default case';
            break;
}

// Fixed 👍
switch ($expr) {
    case 1:
        echo 'First case';
        break;
    case 2:
        echo 'Second case';
        break;
    default:
        echo 'Default case';
        break;
}
```
