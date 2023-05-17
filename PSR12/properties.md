## Properties

### PSR12.Properties.ConstantVisibility

Verifies that all class constants have their visibility set.

```php
// Error 👎
class Foo
{
    const BAR = 'bar';
}

// Fixed 👍
class Foo
{
    public const BAR = 'bar';
}
```
