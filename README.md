```php
<?php


namespace Github\iteplenky;


class About extends Me
{
    /**
     * @return array
     */
    public function getCurrentWorkplace() : array
    {
        return [
            'workplace' => [
                'company' => 'Bedrock Models',
                'position' => 'Creator'
            ]
        ];
    }

    /**
     * @return array
     */
    public function getDailyKnowledge() : array
    {
        return [
            Php::class,
            Javascript::class,
            Html::class,
            Css::class
        ];
    }

    /**
     * @return string
     */
    public function getFutureGoal() : string
    {
        return 'To contribute to open source.';
    }
}
```
