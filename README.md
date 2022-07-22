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
Markdown   10 mins         ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   37.80 %
YAML       8 mins          ⣿⣿⣿⣿⣿⣿⣿⣶⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   30.71 %
HTML       7 mins          ⣿⣿⣿⣿⣿⣿⣷⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   27.21 %
Other      0 secs          ⣦⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀   02.27 %
```

<!--END_SECTION:waka-->
