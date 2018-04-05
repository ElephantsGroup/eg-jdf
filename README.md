jdf
===
Yii2 Jalali date library based on jdf library for yii2 by Hooman.Mirghasemi

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist elephantsgroup/eg-jdf "*"
```

or add

```
"elephantsgroup/eg-jdf": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php 
use elephantsGroup\jdf\Jdf;
?>
<?= Jdf::jdate('H:i:s'); ?>```


This extension built with http://jdf.scr.ir/ you can get full document there.

