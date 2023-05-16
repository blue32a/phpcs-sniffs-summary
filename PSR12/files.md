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

### PSR12.Files.ImportStatement

Verifies that import statements are defined correctly.

```php
// Error 👎
use \DateTime;


// Fixed 👍
use DateTime;
```

### PSR12.Files.OpenTag

Checks that the open tag is defined correctly.

```php
// Error 👎
<?php namespace App;


// Fixed 👍
<?php
namespace App;
```
