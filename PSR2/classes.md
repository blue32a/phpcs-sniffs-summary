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
