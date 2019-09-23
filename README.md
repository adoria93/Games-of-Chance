# Games-of-Chance

Games of Chance is a Python project that I used in order to help me understand more about Python. Currently, the program is VERY basic and you will have to manually call each funtion in order to use them. The functions are:
- coin_flip
- cho_han
- cards
- roulette

You start with 1000 credits.

In the future, I'd like to have it set up to where you can play the same game multiple times in a row without stopping unless you choose to. For each game, the amount you bet must be less than the total amount of credits you have. (That is, you can't bet more than you have!)

# coin_flip(guess, bet)

coin_flip is a game where you have to guess if a coin will land on "Heads" or "Tails". If you guess corrrectly, you win!

# cho_han(guess, bet)

cho_han is a game where you have to guess if the sum of two dice rolls is "Even" or "Odd". If you guess correctly, you win!

# cards(bet)

cards is a game where you will be randomly assigned a card from a deck of cards. The game will then pick another card from that deck after removing the one you picked. If your card is higher than the computer's draw, you win!

# roulette(guess, bet)

roulette is a game where a "ball" is spun around a wheel until it stops. For this game, the American version of roulette is used (numbers 1-36 as well as a "0" and a "00" space). Currently supported bets, each with different payouts, are:
- "Odd"/"Even" 1:1
- "Red"/"Black" 1:1
- "First"/"Second"/"Third" 2:1
- "0"/"00" 35:1
- Specific Number ("1" through "36") 35:1

The bet you choose goes in the "guess" argument.

NOTE: If you guess higher than "36" or lower than "0", the game will still run as normal, but you will always lose. A future update will correct this behaviour to force a choice that is within the range of the game.
