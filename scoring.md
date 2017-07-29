# Scoring

This is a list of tested scoring systems for Chinese Whist.

For reference, a player has "met" a contract if they have won tricks equal to the number of tricks they made the contract for.

## Classic

The scoring system as it was originally introduced to me. This rewards successfully making contracts, and higher numbers of tricks. Making a contract for zero tricks is usually only worth it if no tricks can reliably be won.
- If a contract for zero has been met, the player gains 5 points.
- If a contract for more than zero has been met, the player gains points equal to the contract plus 10.
- If the contract was not met, the player gains points equal to the number of tricks they won.

### Classic with variable zero

This variation on *Classic* better rewards making zero contracts at higher numbers of tricks.
- If a contract for zero has been met, the player gains points equal to the total number of tricks being played for this round.

### Classic with progressive scoring

These variations on *Classic* reward succesful contracts much better the higher the value of the contract, and encourage riskier bidding.

#### Agressive

Has the caveat that successful contracts of more than 6 tricks can be game-ending, use with caution in games that go to 13.
- If a contract for more than zero has been met, the player gains points equal to the square of the contract plus 10.

#### Moderate

- If a contract for more than zero has been met, the player gains points equal to the contract'th Triangle Number plus 10. For example, a met contract of 5 tricks scores 15+10=25 points, and a met contract of 3 tricks scores 6+10=16 points.

#### Conservative

- If a contract for more than zero has been met, the player gains points equal to three times the contract plus 10.

## Oy Vey

From the Whist-like game *Oy Vey*. Heavily rewards precision.
- If a contract was met,the player gains points equal to the contract plus 10.
- If a contract is not met, the player loses points equal to the difference between the number of tricks won and the value of the contract.

## Negative Scoring

This encourages accuracy in and does not differentiate in the size of the contract.
- The player loses points equal to the square of the difference between their contract and the number of tricks they won.
