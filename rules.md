# Rules

You will need:
- 3-5 players (4 is optimal)
- A standard deck of playing cards
- Pen and paper

As a general note, Aces are high in this game.

## Setup

Decide how long you want to play for, and choose a setup accordingly. It is recommended that you use one of the following setups:
- Long: 13->6->13 (not possible with 5 players)
- Medium: 10->4->10
- Short: 10->7->10

For each setup, the first number is the number of tricks played for in the first round. In each subsequent round, one fewer trick is dealt until the middle number is reached. The middle number of tricks is played for again, and thereafter one more trick is dealt each round until the last number is reached. Then the game ends.  
For example, if the setup was 10->7->10, the rounds would go: 10-9-8-7-7-8-9-10.

Select a dealer arbitrarily.

Choose a scoring system (a list of tested scoring systems are available in **scoring.md**).

## Rounds

In each round:
- The dealer shuffles the deck well and deals cards to each player equal to the number of tricks being played for. Players may then look at their hands.
- Trumps are chosen as follows:
  - If this is the first round, there are **No Trumps**.
  - Otherwise, the player who made the highest successful contract in the last round chooses trumps, out of **Diamonds**, **Hearts**, **Spades**, **Clubs**, and **No Trumps**.
    - If two or more players are tied for the higest successful contract, they cut the deck to determine who chooses trumps.
    - If no player made their contract last round, there are **No Trumps**.
- Contracts are made, starting with the player to the left of the dealer, as follows:
  - Each player predicts a number of tricks that they think they can win (in the scoring systems, there is an incentive for predicting this correctly), and this number is recorded. This is their contract for the round.
  - The dealer (the player who makes their contract last), may not choose a number such that the total of all the contracts equals the number of tricks being played for, for example when playing for 6 tricks, if the other players have made contracts totalling 4 tricks, the dealer may not make a contract of 2.
- The tricks are played, with the player to the left of the dealer leading the first trick, as follows:
  - The leader of the trick plays a card face up on the table, without restriction.
  - Going clockwise, every player plays a card. If they have a card of the same suit as the leading player's card, they **must** play it, otherwise they may play any card.
  - After all players have played one card, the winner of the trick is the player who played the highest trump, or failing that, the player who played the higest card of the same suit as the leading player. The winner of the trick collects the cards and places them face down in front of them. The winner of the trick leads the next trick.
- When all tricks have been played, each player counts the number of tricks they won, and the scores for that round are determined.
- The dealer for the next round is the player to the left of the current dealer.

## Winner

After all rounds have been played, the player with the highest score is declared the winner.
