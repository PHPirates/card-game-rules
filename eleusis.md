# Eleusis

Rules adapted from https://web.archive.org/web/20190822201119/http://www.matuszek.org/eleusis1.html

Eleusis can be played with 3 players or more, ideally 4 or 5.

## Cards

The game is played with one standard deck. If during the game more cards are needed, more decks can be added. On average about one deck per three persons is needed.

## Definitions
* Default increasing rank order (by convention, not enforced): A-2-3-4-5-6-7-8-9-10-J-Q-K 

## Play

The dealer first invents a rule which specifies which cards are allowed to be placed at the end of a sequence of cards, possibly depending on previous cards in the sequence or anything else in the environment.
The idea is that the other players will try to guess the rule.

### Deal

The dealer deals 14 cards to each player except himself.
Now the dealer may give hints about the rule.
This includes placing one or more cards in sequence upon the table: the number of cards suggests by convention the number of cards that the rule depends on.
The player next to the dealer (in clockwise direction) starts.
After the first card is played, the dealer is strictly forbidden to give hints.

### A turn

When it is your turn, you can play a sequence of cards of length 1 or more, attached to the already present sequence, or declare a 'no play'.

* In the case cards were played, when the complete sequence is added to the table, the dealer will declare the complete sequence right or wrong, in the case of wrong without saying which cards are wrong.
    * When the sequence is right, they stay were they are.
    * When the sequence is wrong, they will be moved sideways such that they are next to the present sequence (see [logicmazes.com](http://www.logicmazes.com/games/eleusis/layout.gif) for an example) (often it is practical to stack them in the same orientation when wrong sequences of 1 card are played, and turn them 90 degrees when a sequence of more than 1 card was wrong, to distinguish these two cases).
    The player gets two penalty cards dealt for each wrong card played.
* In the case of a 'no play', the cards are put open on the table and the dealer will check whether this call is correct.
    * If correct, and the player has n cards, the player will get a completely new hand dealt consisting of max(n-4,0) cards, i.e. the player will have no cards left if n <= 4.
    * If incorrect, the dealer takes one card out of the hand which is valid to add to the sequence, and plays it. The player gets 5 penalty cards.

#### Prophet
At the end of a turn, the player may declare himself a Prophet if there is not already a Prophet.
In that case, the Prophet will from now on declare right and wrong, and (perhaps temporarily) puts his cards away.
The Prophet puts a black marker on the last card played before he became Prophet, and every 10th card after that.
The Prophet will be checked by the dealer, if he makes a mistake he will get 5 penalty cards, all black markers are removed and he is a normal player again.
If he made a mistake when a player played a sequence, the player who played the sequence will not get penalty cards.
If he made a mistake when a player declared a 'no play', the player will get his cards back.

#### Other rules
On every 10th card played, put a white marker.
The first sequence which starts with a card in the 41st position or higher if there are no black markers, or the 31st position or higher after the first black marker, will start a sudden death period: every player who does an action (a sequence or no play) which is wrong as determined by God (not the prophet, who will continue as a player if he makes a mistake) will be inactive until the round ends.

The round ends when all players are inactive, or when one player has no cards anymore.

### Scoring

* Find the high count: the largest number of cards held by any player (including the prophet). Everyone except the dealer gets a number of points equal to the high count minus the number of cards in his hand. 
* Anyone (except the dealer) with no cards at all gets a 4 point bonus.
* If there was a Prophet at the end of the game, he gets 1 1 point for each right card and 2 points for each wrong card played after he became prophet. 
* The dealer's score is the smaller of (a) the highest player's score, or (b) twice the number of cards played before the first black marker if one exists.

### Continuing play

Now the next player after the dealer becomes the new dealer, and play starts again.
The game ideally ends when everyone has been a dealer the same number of times.
