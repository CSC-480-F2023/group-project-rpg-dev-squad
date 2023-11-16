# **<ins>Personas</ins>:**
Persona: Johnny Sayer (User)\
I am a gamer who loves combat style games. I like combat that is rewarding and have multiple facets to approach and defeat an enemy.

Persona: Taylor Yannas (User)\
I am a gamer who loves a great environment. I love to interact with the things around me and move in big spaces while having the immersion that there is more to explore.

Persona: Diana Kyasha (Acquirer)\
As an investor, I would like for the product to have great performance while making it accessible to the user of the product during use.

Persona: Darack Yestuday (Regulator)\
As an auditor, I would like to have ease of use and accessibility from the product. I also would like for minimal bugs and for the game to ensure user intensions through an interactable interface.

Persona: Derald Todder (Producer)\
As a game developer, I would like players to have great replayability though progression, such as the want to chase something. 

Persona: John Porker (Producer)\
I am a graphics designer who likes information to be conveyed in a visually appeasing way. I would like for the game to have an informative interface when going through combat and exploring the game's world. I would also like clear indications of actions and occurances a user should know about.

# **<ins>Functional Requirements</ins>:**

## Combat:
When the player interacts with an enemy, the system shall initiate a combat interface within 2 seconds.

The combat interface shall display player options in 4 buttons which will allow the player to attack, open bag, use skill, or run.
- The attack button shall initiate a default attack against the enemy based on the player's equipped weapon.
- The open bag button shall display the consumable items from the player's inventory that will aid in battle.
- The skill button shall display 4 buttons that represent different skills the player's character can use which consumes skill points depending on the specific skill.
  - Skills shall attack or defend against the enemy, buff the player's character, or debuff the enemy.   
- The run button shall make the player leave the battle and close the combat interface.

The combat interface shall display and update the status of the player and the enemy until the end of the combat.

When the player defeats an enemy, the player and player's equipped items will obtain EXP depending on the enemy level, a chance for a random item to drop, and the combat interface will close.

## Exploration:
When player use movement keys, the system shall move the player's character as long as the keys are still pressed.

When the player appraches an item or chest, the system shall allow the player to interact with it if the player presses the required button.
- When the player interacts with a chest, the system shall give the player a random item from a predetermined item loot pool.
- When the player interacts with an item, the system shall give the player that item.

When the player hits an entrance to another area, the system should allow the player to enter the area with the press of a designated key.
- When the player presses the designated key to enter an area, the system should load the area and the player's character within 2-6 seconds.

When the player hits the edge of the map, the system should prevent the player from going beyond the bounds of the map.

## Equipment items:
When an equipment item is given to the player, the system shall give the item random stats or abilities.

When an equipment item reaches max EXP, the item will level up. 
- When an equipment item levels up, the system will increase the item's stats by random amounts and/or assign a random ability to that item.

## General Items:
A general items shall be generated in the world at random locations or in a chest.

A general item can be obtain through defeating enemies as a random drop.

A general item shall be used to aid in battle or to level up equippable items.

# **<ins>Non-functional Requirements</ins>:**
## Combat:
The combat interface shall display the player and the enemy facing each other.

The combat interface shall display small animations when player or enemy does an actions

## Exploration:

When the player hits the edge of the map, the system should inform the player that they can't go further.

## Equipment items:
When an equipment item is obtain, the item will appear on screen with the items stats displayed until the player presses a designated key to close the display.

When an equipment item levels up, the system will display a "Level Up!" text with the items that leveled up until the player selects a designated key to close the text.

## General Items:
When a general item it obtained, the system will display the item on the side of the screen for 3 seconds.
