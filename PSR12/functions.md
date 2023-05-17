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

### PSR12.Functions.ReturnTypeDeclaration

Ensure return types are defined correctly for functions and closures.

```php
// Error 👎
function foo(int $int) :int
{
    return $int;
}

// Fixed 👍
function foo(int $int): int
{
    return $int;
}
```
