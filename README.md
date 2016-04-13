Very simple php thumbnail
===================

This is a very simple component that to generate image thumbnail by PHP

Usage
-----------
```php
<?php

require 'SimpleThumbnail.php';

SimpleThumbnail::create()->image('source_image.jpg')->thumbnail(300)->to('destination_thumbnail_image.jpg');

?>
```
