## Files

### PSR2.Files.ClosingTag

Checks that the file does not end with a closing tag.

```php
// Error 👎
<?php
echo 'Foo';
?>

// Fixed 👍
<?php
echo 'Foo';
```

### PSR2.Files.EndFileNewline

Ensures the file ends with a newline character.

```php
// Error 👎
<?php
echo 'Foo';EOF

// Fixed 👍
<?php
echo 'Foo';↩
EOF
```
