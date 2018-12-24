# ApkPacker
Using PHP to create APK channel package

Installation
------------

Use composer to manage your dependencies and download JWT:

```bash
composer require xiaozhuangyuan/apkpacker
```

Example
-------
```php
<?php
use xiaozhuangyuan\ApkPacker\ApkPacker;
    //Create ApkPacker Object

    $apkPacker = new \ApkPacker\ApkPacker();

   //Call packerSingleApk function to write channelName into apk

    $apkPacker->packerSingleApk('source.apk','channelName',"target.apk");

```

