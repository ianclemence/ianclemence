
<?php
namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'MEA Mobile',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            CSS::class,
            Python::class,
            PHP::class,
            Wordpress::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}

