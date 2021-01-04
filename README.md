```php
<?php

namespace Ian Clemence;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => "Currently i'm a Freelancer",
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
            Sql::class,
            Laravel::class,
            Css::class,
            Html::class,
            Aws::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
