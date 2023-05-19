## Namespaces

### PSR2.Namespaces.NamespaceDeclaration

Ensures namespaces are declared correctly.

```php
// Error 👎
namespace App;
use Foo;

// Fixed 👍
namespace App;

use Foo;
```

### PSR2.Namespaces.UseDeclaration

Ensures USE blocks are declared correctly.

```php
// Error 👎
use Foo, Bar;

// Fixed 👍
use Foo;
use Bar;
```
