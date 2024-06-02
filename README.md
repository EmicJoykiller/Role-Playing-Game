Core Features:

Player Stats and Inventory Management:

Track player stats such as XP, health, and gold.
Manage an inventory of weapons, starting with a basic "stick" and progressing to more powerful weapons like daggers, claw hammers, and swords.
Interactive Locations:

Town Square: The central hub where players can decide their next move.
Store: Buy health and weapons to prepare for battles.
Cave: Explore and fight different monsters, including slimes and fanged beasts.
Fight Mode: Engage in battles with the monsters encountered.
Combat System:

Fight against various monsters with different levels and health points.
Attack and dodge mechanics to make combat interactive.
Randomized damage and hit chances to add unpredictability.
Winning and Losing Conditions:

Players win by defeating the dragon.
Players lose if their health drops to zero.
Special Features:

Easter Egg: A hidden mini-game where players can win gold by guessing numbers.
Weapon Breakage: Weapons have a chance to break during combat, adding a layer of strategy.
User Interface:

HTML Structure:

game div: Main container for the game.
stats div: Displays player stats.
controls div: Buttons for player actions.
monsterStats div: Displays current monster's stats during combat.
text div: Main text area for game narrative and updates.
CSS Styling:

Dark theme with a medieval aesthetic.
Buttons and stats styled for clarity and ease of use.
JavaScript Logic:

Game Initialization:

Initialize variables for XP, health, gold, current weapon, and inventory.
Set up event listeners for buttons to trigger game actions.
Location Updates:

Functions to navigate between different locations in the game.
Update the interface based on the current location and actions taken.
Combat Mechanics:

Functions for attacking, dodging, and determining combat outcomes.
Randomized elements for hit chances and damage calculation.
Resource Management:

Functions for buying health and weapons, selling weapons, and managing inventory.
Game End Conditions:

Functions to handle winning, losing, and restarting the game.
