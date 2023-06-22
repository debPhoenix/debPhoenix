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

```txt
Vue.js       1 hr 14 mins    ⣿⣿⣿⣿⣿⣿⣷⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   27.13 %
Makefile     51 mins         ⣿⣿⣿⣿⣶⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   18.87 %
TypeScript   36 mins         ⣿⣿⣿⣤⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   13.20 %
YAML         32 mins         ⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   11.74 %
Other        24 mins         ⣿⣿⣄⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   08.90 %
```

<!--END_SECTION:waka-->
