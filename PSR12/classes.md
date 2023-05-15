## Classes

### PSR12.Classes.AnonClassDeclaration

Checks that the declaration of an anon class is correct.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr12classesanonclassdeclaration)

```php
// Error 👎
new class implements 
  \ArrayAccess
{
};

new class implements 
    \ArrayAccess,
    \Countable {
};

// Fixed 👍
new class implements 
    \ArrayAccess
{
};

new class implements 
    \ArrayAccess,
    \Countable
{
};
```

### PSR12.Classes.ClassInstantiation

Verifies that classes are instantiated with parentheses.

```php
// Error 👎
new \DateTime;

// Fixed 👍
new \DateTime();
```
