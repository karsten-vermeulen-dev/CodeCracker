## Try the following: 

<b>1.</b> Create a <i>Player</i> class and the inheriting classes <i>Orc</i>, <i>Elf</i> and <i>Human</i> <br>
<b>2.</b> Make sure the <i>Player</i> class has following member variables:

```cpp
m_health
m_attackPower
```

<b>3.</b> Make sure that <i>m_attackPower</i> is only visible for the <i>Player</i> class and inheriting classes. The variable <i>m_health</i> should be visible to any other class.

<b>4.</b> Add the following default values to the classes:

<b>Orcs</b>: <b>120</b> health, <b>10</b> attackPower <br>
<b>Humans</b>: <b>90</b> health, <b>10</b> attackPower <br>
<b>Elves</b>: <b>60</b> health, <b>15</b> attackpower	<br>

<b>5.</b> The <i>Player</i> class should contain an overwritable function called <i>Attack()</i> that will reduce the health value of other player by the attack power of the attacking Player. The function should looks like this:

```cpp
void Attack(const Player& otherPlayer);
```

<b>6.</b> Implement the following additional features within the inheriting classes:

<b>a.</b> Orcs have a <b>20%</b> chance of missing an attack. <br>
<b>b.</b> Orcs have a <b>30%</b> chance of doing double damage, which also damages the attacking orc by his own attack power. <br>
<b>c.</b> Humans have a <b>50%</b> chance of doing <b>50%</b> additional damage. <br>
<b>d.</b> Elves have a <b>30%</b> chance of doing five points less damage and healing them by ten points (Consider maximum health levels). <br>

<b>7.</b> When the game starts, the player can choose a race. After that, the battle starts automatically and lasts until one player is dead. The main game loop could look something like this:

```cpp
while(m_health > 0)
{
    //play the game...
}
```

<b>8.</b> Implement suitable console input and output for the game. <br>

### Bonus <br>

Think of suitable additions to the game (e.g., potions of new races) and implement one of those additions.
