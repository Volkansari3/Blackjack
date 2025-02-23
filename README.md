Blackjack Game in Python

- This is a command-line Blackjack game implemented in Python using Object-Oriented Programming (OOP) principles. 
- The game simulates a standard Blackjack scenario where a player competes against a dealer. 
- It features classes for cards, deck, player, and dealer, and supports common Blackjack actions such as hit, stand, double down, split, and surrender.

Gameplay Instructions

Starting the Game:
- Upon launching the game, you will be prompted to enter your name.
- You begin with a default balance (e.g., 2000).

Placing a Bet:
- At the start of each round, you will be asked to place a bet.
- The bet must be a positive number and cannot exceed your current balance.

Player Actions: During your turn, you can choose one of the following actions:

- Hit (H): Draw another card.
- Stand (S): End your turn and keep your current hand.
- Double Down (D): Double your bet and receive one additional card.
- Split (SP): If your first two cards have the same value, split them into two separate hands.
- Surrender (Q): Surrender the hand, losing half of your bet.

Dealer's Turn:
Once you have completed your actions, the dealer reveals the hidden card and draws cards until reaching at least 17 points.

Determining the Outcome:
-If your hand exceeds 21, you bust.
-If the dealer busts, you win.
-If neither busts, the hand with the higher total wins.
In the event of a tie, your bet is returned.
