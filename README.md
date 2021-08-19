```php
<?php

namespace DebPhoenix;

class About extends Me
{
    public function getCurrentStatus(): array
    {
        return [
            'status' => [
                'position' => 'Web Student',
                'school' => 'M2i'
            ]
        ];
    }

    public function getTechs(): array
    {
        return [
            Php::class,
            Javascript::class,
            Symfony::class,
            React::class,
            MySQL::class,
            Swift::class,
            Bootstrap::class,
            Sass::class,
            Git::class
        ];
    }

    public function getSomethingMore(): string
    {
        return "I don’t trust people who don’t write SQL queries in uppercase";
    }
}
```
