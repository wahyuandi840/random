# random
Libary Sederhana Untuk Membuat String Acak
Download package dengan composer
```
composer require wahyuandi840/random
```
atau
```
{
	"require": {
		"wahyuandi840/random" : "dev-master"
	}
}
```
Penggunaan
Dengan String Default
```php
//membuat membuat acak default
$pajang=32;
$random=new Wahyu\Random();
echo $random->string($panjang);
```
Dengan String Custom
```php
$random->string="ABCUHEHGDH773287309";
echo $random->string(10);
```
