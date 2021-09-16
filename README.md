## iliyagram, Bot Api Library
**Created By: [Iliya Gholami](https://t.me/dr_eliya)**<br>
**Document: <https://iliyagram.tk>**

### What is an Iliagram?

Convenient library for working with Telegram Bot Api, designed with Telegram templates, receiving updates from Telegram with two methods getUpdates and php input!

### Getting started
```php
<?php
require 'vendor/autoload.php';

$bot = new Iliyagram\Bot('API_TOKEN');
echo $bot->getMe();
$bot->close();

```
