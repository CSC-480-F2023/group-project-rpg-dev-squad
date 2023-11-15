# **<ins>Functional Requirements</ins>:**
## Combat:
When the player interacts with an enemy, the system shall initiate a combat interface within 2 seconds.

The combat interface shall display player options in 4 buttons which will allow the user to attack, open bag, use skill, or run.
- The attack button shall initiate a default attack against the enemy based on the player's equipped weapon.
- The open bag button shall display the consumable items from the player's inventory that will aid in battle.
- The skill button shall display 4 buttons that represent different skills the player's character can use which consumes skill points depending on the specific skill.
  - Skills shall attack or defend against the enemy, buff the player's character, or debuff the enemy.   
- The run button shall make the player leave the battle and close the combat interface.

When the player defeats an enemy, the player and player's equipped items will obtain EXP depending on the enemy level, a chance for a random item to drop, and the combat interface will close.

## Exploration:
When player use movement keys, the system shall move the player's character as long as the keys are still pressed.

When the player appraches an item or chest, the system shall allow the player to interact with it if the player presses the required button.
- When the player interacts with a chest, the system shall give the player a random item from a predetermined item loot pool.
- When the player interacts with an item, the system shall give the player that item.

When the player hits an entrance to another area, the system should allow the player to enter the area with the press of a designated key.
- When the player presses the designated key to enter an area, the system should load the area and the player's character within 2-6 seconds.

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

When the player hits the edge of the map, the system should inform the user that they can't go further.

## Equipment items:
When an equipment item is obtain, the item will appear on screen with the items stats displayed until the player presses a designated key to close the display.

When an equipment item levels up, the system will display a "Level Up!" text with the items that leveled up until the player selects a designated key to close the text.

## General Items:
When a general item it obtained, the system will display the item on the side of the screen for 3 seconds.
