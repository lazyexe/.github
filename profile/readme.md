```php
<?php

class Lazy {
    function about () {
        return [
            'name' => 'LazyCode Community',
            'location' => 'Indonesia',
            'Wangsaff' => 'https://chat.whatsapp.com/Cxs447fSIAyGDE4RH266o9'
        ];
    }
}

$lambo = new Lazy();
print_r($lambo->about());
```
