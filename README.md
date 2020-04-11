# Game-of-Chance

The games included in this code are:

+ Coin Flip
+ Cho Han
+ Cards
+ Roulette

---
### Coin Flip

Create a function that simulates flipping a coin and calling either "Heads" or "Tails". This function (along with all of the other functions you will write in this project) should have a parameter that represents how much the player is betting on the coin flip.

This function should also have a parameter that lets the player call either "Heads" or "Tails".

If the player wins the game, the function should return the amount that they won. If the player loses the game, the function should return the amount that they lost as a negative number.

---

### Cho Han

The function should simulate rolling two dice and adding the results together. The player predicts whether the sum of those dice is odd or even and wins if their prediction is correct.

The function should have a parameter that allows for the player to guess whether the sum of the two dice is "Odd" or "Even". The function should also have a parameter that allows the player to bet an amount of money on the game.

---

### Cards

A function that simulates two players picking a card randomly from a deck of cards. The higher number wins.

Once again, this function should have a parameter that allows a player to bet an amount of money on whether they have a higher card. In this game, there can be a tie. What should be returned if there is a tie?

---

### Roulette


roulette is a game where a "ball" is spun around a wheel until it stops. For this game, the American version of roulette is used (numbers 1-36 as well as a "0" and a "00" space). Currently supported bets, each with different payouts, are:

+ "Odd"/"Even" 1:1
+ "Red"/"Black" 1:1
+ "First"/"Second"/"Third" 2:1
+ "0"/"00" 35:1
+ Specific Number ("1" through "36") 35:1
The bet you choose goes in the "guess" argument.

When you guess higher than "36" or lower than "0", the game will still run as normal, but you will always lose.
