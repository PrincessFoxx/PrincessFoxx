```php
<?php

namespace Foxx;

class About extends Me {

  public function __construct() {
    $this->name = 'Foxx';
    $this->age = 18;
    $this->pronouns = ['She/Her', 'It/Its'];
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
      'hobbies' => ['coding', 'archery', 'listening to music'],
      'favoriteFood' => 'lasagna',
      'favoriteColor' => ['name' => 'coral', 'hex' => '#ff7f50'],
      'favoriteNumber' => 42,
      'favoriteAnimal' => 'fox',
      'favoriteShow' => 'Blindspot'
    ];
  }

  public function getCurrentOccupation(): array {
    return [
      'occupation' => [
        'occupation' => 'Student',
        'Grade' => '12'         
      ]
    ];
  }

  public function getSkills(): array {
    return [
      Php::class,
      Javascript::class,
      Html::class,
      Python::class,
      Node::class
    ];
  
  }

  public function GetProjects() {
    return [
      "https://github.com/TheForestSystem/express-learning",
      "Working on a API wrapper for genius.com"
    ]
  }

}
```
