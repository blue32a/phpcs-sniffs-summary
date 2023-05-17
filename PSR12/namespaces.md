## Namespaces

### PSR12.Namespaces.CompoundNamespaceDepth

Verifies that compound namespaces are not defined too deep.

By default, this sniff ensures that the namespaces are no more than two levels deep.

[Custom properties](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Customisable-Sniff-Properties#psr12namespacescompoundnamespacedepth)

```php
// Error 👎
use Vendor\Package\SomeNamespace\{
    SubnamespaceOne\AnotherNamespace\ClassA,
    SubnamespaceOne\ClassB,
    ClassZ,
};

// Fixed 👍
use Vendor\Package\SomeNamespace\SubnamespaceOne\AnotherNamespace\ClassA;
use Vendor\Package\SomeNamespace\{
    SubnamespaceOne\ClassB,
    ClassZ,
};
```
