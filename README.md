Magical Arena Game:

Welcome to the Magical Arena Game! This project simulates a turn-based battle between two players in a magical arena. Players are defined by their "health," "strength," and "attack" attributes, all represented by positive integers. The objective is to reduce the opponent's health to zero through strategic attacks and defenses.

Game Mechanics:
Player Attributes:-
Health: Represents the player's life points. The player is defeated when health reaches zero.
Strength: Determines the defender's ability to withstand attacks.
Attack: The offensive power of the player, influencing the damage inflicted on the opponent.

Turn-based Combat:
Players take turns attacking and defending.
The attacking player rolls a six-sided die to determine the attack outcome.
The defending player rolls a six-sided die to determine the defense outcome.

Damage Calculation:
Attack damage is calculated as the product of the attack attribute and the attacking dice outcome.
Defense strength is calculated as the product of the strength attribute and the defending dice outcome.
Excess attack damage over defense strength reduces the defender's health.

Game End:
The game ends when the health of any player reaches zero.
The player with the higher health at the end of the game is declared the winner.

Initial Conditions:
The player with lower health attacks first.
Example initial conditions: Player A (50 health, 5 strength, 10 attack) vs. Player B (100 health, 10 strength, 5 attack).

Example Turn:-
Player A attacks, rolls a die (5), and inflicts damage (5 * 10 = 50).
Player B defends, rolls a die (2), and defends against some damage (10 * 2 = 20).
Player B's health is reduced by the excess damage (50 - 20 = 30), resulting in a new health value of 70.
The game continues with turns alternating between players.


How to Run:-
Open the HTML file in a web browser which is connect with server.css file.
Fill in the initial attributes for Player A and Player B.
Click the "Start Game" button to initiate the battle.