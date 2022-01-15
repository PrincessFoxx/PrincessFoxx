```php
<?php

namespace Foxx;

class About extends Me {

  public function __construct() {
    $this->name = 'Foxx';
    $this->age = 15;
    $this->pronouns = ['she/her', 'they/them'];
  }

  public function getCredit() {
    return "https://github.com/ashbakernz";
  }

  public function getBaseInfo() {
    return [
      'name' => $this->name,
      'age' => $this->age,
      'pronouns' => $this->pronouns,
      'discription' => "I'm mostly a backend developer, though i'm learning a lot about frontend development.",
      'funFact' => "Like a guided missile, the fox harnesses the Earth's magnetic field to hunt. Other animals, like birds, sharks, and turtles, have this “magnetic sense,” but the fox is the first one we've discovered that uses it to catch prey.",
      'hobbies' => ['coding', 'video games', 'listening to music'],
      'favoriteFood' => 'lasagna',
      'favoriteColor' => ['name' => 'aqua', 'hex' => '#00FFFF'],
      'favoriteNumber' => 42,
      'favoriteAnimal' => 'fox',
      'favoriteShow' => 'Blindspot'
    ];
  }

  public function getCurrentOccupation(): array {
    return [
      'occupation' => [
        'occupation' => 'Student',
        'Grade' => '10'         
      ]
    ];
  }

  public function getDailyKnowledge(): array {
    return [
      Php::class,
      Javascript::class,
      Html::class,
      Python::class,
      Node::class
    ];
  }

  public function getFutureGoal(): string {
    return 'To complete at the least, one project';
  }
}

```
