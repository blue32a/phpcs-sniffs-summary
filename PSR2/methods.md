## Methods

### PSR2.Methods.FunctionCallSignature

Checks that the function call format is correct.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr2methodsfunctioncallsignature)

```php
// Error 👎
somefunction( $foo, $bar );

somefunction2(
  $foo,
    $bar);

// Fixed 👍
somefunction($foo, $bar);

somefunction2(
    $foo,
    $bar
);
```

### PSR2.Methods.FunctionClosingBrace

Checks that the closing brace of a function goes directly after the body.

```php
// Error 👎
function foo()
{
    echo 'foo';

}

// Fixed 👍
function foo()
{
    echo 'foo';
}
```

### PSR2.Methods.MethodDeclaration

Checks that the method declaration is correct.

```php
// Error 👎
abstract class MyClass
{
    public abstract function foo();
    public final function bar() {}
}

// Fixed 👍
abstract class MyClass
{
    abstract public function foo();
    final public function bar() {}
}
```
