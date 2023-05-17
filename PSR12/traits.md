## Traits

### PSR12.Traits.UseDeclaration

Verifies that trait import statements are defined correctly.

```php
// Error 👎
class Foo
{
    public const BAR = 'bar';
    use FooTrait;
}

// Fixed 👍
class Foo
{
    use FooTrait;

    public const BAR = 'bar';
}
```
