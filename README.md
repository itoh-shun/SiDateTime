# SiDateTime

Creator: Shun Itoh by Spiral Inc.

このプログラムはスパイラル社のSpiral v1で利用できます。
```php
<?php
//<!-- SMP_DYNAMIC_PAGE DISPLAY_ERRORS=OFF NAME=xxx -->
require_once 'SiDateTime/require.php';

$date = new SiLibrary\SiDateTime('2024年04月12日');

var_dump($date->format("Y-m-d"));//2024-04-12