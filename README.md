```php
<?php

namespace Ian Clemence;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'KCMC',
                'position' => 'Web Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Python::class,
            SQL::class,
            Laravel::class,
            CSS::class,
            HTML::class,
            Aws::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
