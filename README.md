Very simple php thumbnail
===================

This is a very simple component that to generate image thumbnail by PHP

Use age
-----------
```php
<?php
require 'SimpleThumbnail.php';
SimpleThumbnail::start()->image('source_image.jpg')->thumbnail(300)->to('destination_thumbnail_image.jpg');
?>
```