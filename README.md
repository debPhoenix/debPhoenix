```php
<?php

namespace DebPhoenix;

class About extends Me
{
    public function getCurrentStatus(): array
    {
        return [
            'status' => [
                'position' => 'Web Dev Student',
                'type' => 'front-end & back-end lover'
            ]
        ];
    }

    public function getTechs(): array
    {
        return [
            Php::class,
            Symfony::class,
            MySQL::class,
            Javascript::class,
            React::class,
            Swift::class,
            Bootstrap::class,
            Sass::class,
            Git::class
        ];
    }

    public function getExtra(): string
    {
        return "Here is the place I test and break things to learn!";
    }
}
```


<!--START_SECTION:waka-->

```text
Vue.js           10 hrs 18 mins  ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣀⣀⣀⣀⣀⣀   74.40 %
Python           1 hr 47 mins    ⣿⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   12.88 %
TypeScript       54 mins         ⣿⣶⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   06.56 %
JSON             18 mins         ⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.19 %
HTML             11 mins         ⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   01.39 %
XML              6 mins          ⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.80 %
```

<!--END_SECTION:waka-->
