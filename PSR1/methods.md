## Methods

### PSR1.Methods.CamelCapsMethodName

Ensures method names are defined using camel case.

```php
// Error 👎
class Foo {
    public function _Gar_Value() {}
}

// Fixed 👍
class Foo {
    public function garValue() {}
}
```
