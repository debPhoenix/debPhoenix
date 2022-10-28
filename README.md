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
SQL              32 mins         ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   46.18 %
HTML             17 mins         ⣿⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   24.15 %
JSON             14 mins         ⣿⣿⣿⣿⣿⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   19.80 %
JavaScript       5 mins          ⣿⣷⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   07.24 %
XML              1 min           ⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.20 %
Markdown         0 secs          ⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   00.30 %
```

<!--END_SECTION:waka-->
