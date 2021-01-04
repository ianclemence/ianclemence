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
                'position' => "Web Developer"         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::self,
            Python::self,
            Sql::class,
            Laravel::self,
            Css::class,
            Html::class,
            Aws::self,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
