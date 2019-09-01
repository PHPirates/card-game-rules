# name

Rules adapted from https://www.pagat.com/schafkopf/skat.html

Skat is a German game for exactly three players.

## Cards

The game is played with the numbers \[7, A\] (standard rank order) of a standard deck.

## Definitions
* Increasing suit order: :diamonds: :hearts: :spades: :clubs: 
* Increasing rank order for trump suit: 7-8-9-Q-K-10-A-:diamonds:J-:hearts:J-:spades:J-:clubs:J (10 is between K and A, Jacks are high)
* Increasing rank order non-trump suit: 7-8-9-Q-K-10-A (same without Jacks)
* Increasing rank order of trump suit in Grand game: :diamonds:J-:hearts:J-:spades:J-:clubs:J (only Jacks)
* Increasing rank order in null game: standard 

## Play

### Deal

The dealer deals (batches of) three cards to each player, then two cards face down in the centre of the table called the skat, then four and three cards to each player.

### Game value

In order to know what you can bid, you need to know the game values and card points.

The card points are

| Card  | 7 | 8 | 9 | Q | K | 10 | A | J |
| Value | 0 | 0 | 0 | 3 | 4 | 10 | 11 | 2|

The value of a Suit or Grand contract is obtained by multiplying the base value with the multiplier. The base values are in increasing suit order 9, 10, 11 and 12, and 24 for Grand.

| Contract | Base value |
|:---------|:---|
| :diamonds:         | 9           |
| :hearts:         | 10           |
| :spades:         | 11           |
| :clubs:         | 12           |
| Grand         | 24           |

The multiplier is obtained by adding the following values.

| Multiplier  | Explanation |
|---| --- |
| Matadors | The longest sequence of Jacks you have or don't have, starting from the top one |
| Game | Always 1 |
| Hand | 1 if you didn't look at the Skat |
| Schneider | 1 if you took 90 or more card points |
| Schneider announced | 1 if you announced Schneider before playing |
| Schwarz | 1 if you took every trick |
| Schwarz | 1 if you announced Schwarz before playing |
| Open | 1 if you played an Open bid |

A Null game has the following values.

| Contract | Value |
| --- | --- |
| Null | 23 |
| Null Hand (not looking at the Skat) | 35 |
| Null Ouvert | 46 |
| Null Ouvert Hand | 59 |

### Bidding

The possible bids are numbers.
You make your bid if you take at least 61 points and your game value is at least your bid.
The lowest possible game value is :diamonds: with 1 Matador which is 18, so bidding starts at 18.

The player to the dealer's left is called _forehand_, the player to the forehand's left is called _middlehand_ and the player to the middlehand's left (the dealer) is called _rearhand_.
The bidding starts with the middlehand, passing or bidding a number.
Then the forehand can pass or bid.

If the forehand passes, the rearhand can pass, in which case the play starts over, or the rearhand bids in which case the bidding is over.
If the forehand bids, starting with the middlehand the forehand and middlehand bid against each other to determine who wins between them.
They can bid equal values, in which case the forehand wins from the middlehand (who would win from the rearhand). 
When one of them passes, the rearhand can pass or bid, and if the rearhand bids the rearhand bids in the same way against the forehand.

To remember whose turn it is to start the bidding, German players sometimes say "geben, hören, sagen" (deal, listen, speak), pointing in turn to dealer, forehand and middlehand.

### Winning



### A turn

#### Special rules

### Continuing play

<!--What to do after play ends?-->