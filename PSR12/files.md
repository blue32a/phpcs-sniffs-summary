## Files

### PSR12.Files.DeclareStatement

Checks the format of the declare statements.

```php
// Error 👎
declare( strict_types=1);

// Fixed 👍
declare(strict_types=1);
```

### PSR12.Files.FileHeader

Checks the format of the file header.

```php
// Error 👎
<?php
namespace App;


// Fixed 👍
<?php

namespace App;
```
