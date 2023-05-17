## Functions

### PSR12.Functions.NullableTypeDeclaration

Verifies that nullable typehints are lacking superfluous whitespace, e.g. ?int

```php
// Error 👎
function foo(? int $int)
{
}

// Fixed 👍
function foo(?int $int)
{
}
```
