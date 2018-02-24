
Yii2 jalali date class

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require --prefer-dist behnam-rasouli/yii2-jdate "dev-master"
```

or add

```
"behnam-rasouli/yii2-jdate": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

simply use it in your code by  :


```php
new \jdate\Jdate();```


example : 
```php
$date = new \jdate\Jdate();
echo $date->date('Y/m/d H:i', time());
```
	

# yii2-jdate
Yii2 jalali date class


Good luck :)
