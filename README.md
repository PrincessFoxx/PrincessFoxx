```php
<?php

namespace Foxx;

$credit = "https://github.com/ashbakernz"

class About extends Me
{
    public function getCurrentPccupation(): array
    {
        return [
            'occupation' => [
                'occupation' => 'Student',
                'Grade' => '10'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Html::class,
            Python::class
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To complete at the least, one project';
    }
}
```
