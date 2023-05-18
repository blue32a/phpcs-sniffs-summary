## Classes

### PSR2.Classes.ClassDeclaration

Checks the declaration of the class and its inheritance is correct.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr2classesclassdeclaration)

```php
// Error 👎
class Foo {
}

class Bar  extends Foo implements
  \ArrayAccess,
    \Countable
{
}

// Fixed 👍
class Foo
{
}

class Bar extends Foo implements
    \ArrayAccess,
    \Countable
{
}
```

### PSR2.Classes.PropertyDeclaration

Verifies that properties are declared correctly.

```php
// Error 👎
class Foo
{
    var $a;
    private $_b;
    protected $c, $d;
}

// Fixed 👍
class Foo
{
    public $a;
    private $b;
    protected $c;
    protected $d;
}
```
