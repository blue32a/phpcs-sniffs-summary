## Keywords

### PSR12.Keywords.ShortFormTypeKeywords

Verifies that the short form of type keywords is used (e.g., int, bool).

```php
// Error 👎
$int = (integer) '123';
$bool = (boolean) 1;

// Fixed 👍
$int = (int) '123';
$bool = (bool) 1;
```
