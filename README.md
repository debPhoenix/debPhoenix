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

    public function getSomethingMore(): string
    {
        return "Here is the place I break things to learn!";
    }
}
```


<!--START_SECTION:waka-->
📊 **This Week I Spent My Time On** 

```text
⌚︎ Time Zone: Europe/Paris

💬 Programming Languages: 
PHP                      9 hrs 23 mins       █████████████░░░░░░░░░░░░   52.73% 
Twig                     3 hrs 13 mins       ████░░░░░░░░░░░░░░░░░░░░░   18.08% 
JavaScript               1 hr 55 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.78% 
Markdown                 1 hr 48 mins        ██░░░░░░░░░░░░░░░░░░░░░░░   10.12% 
SCSS                     47 mins             █░░░░░░░░░░░░░░░░░░░░░░░░   4.48%

🔥 Editors: 
VS Code                  17 hrs 49 mins      █████████████████████████   100.0%

💻 Operating System: 
Mac                      17 hrs 49 mins      █████████████████████████   100.0%

```


 Last Updated on 12/09/2021
<!--END_SECTION:waka-->
