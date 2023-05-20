## Files

### PSR1.Files.SideEffects

Ensures a file declares new symbols and causes no other side effects, or executes logic with side effects, but not both.

[Side Effects - PSR-1: Basic Coding Standard - PHP-FIG](https://www.php-fig.org/psr/psr-1/#23-side-effects)

```php
// Error 👎
include 'foo.php';
class Bar {}
```
