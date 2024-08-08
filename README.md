# Prime - A Short Card Game for Solo Play
Prime, originally called 'suicide', was a card game I made up when I was a kid which is a solitaire like game that could be played on an airplane tray.  The games are short and can be played within a few minutes.

During the play, the player will make 4 piles of cards following suit.  The rules determine if a card can be played on top of a previous card.  Cards that cannot be played will be discarded.  The goal of the game is to have as small of a discard pile as possible.

Kings, Jacks, and 7's are the most difficult to land, hence this game is called Prime as they are prime numbers.

(Edit: There is another card game called [Prime](https://www.pagat.com/invented/prime.html) as well which was made for multiple players)

# Rules
Start with a shuffled deck.  With the deck face down, pull cards from the top and sort them in piles according to suit, face up.  Heart cards go on top of heart, spade on top of spade, and so on.

Face cards numeric values:
- Jacks = 11
- Queens = 12
- Kings = 13
- Aces = 1

The drawn card can be placed on top of the placed card if they fit within the following rules:

1. The drawn card is +1 of the placed card
   - Example: a 2 is on top of the pile, and the drawn card is a 3
2. The drawn card is divisible by the placed card
   - Example: a 3 is now on top of the pile, and the drawn card is a Queen (12).  12 is divisible by 3
3. The drawn card is LESS than the placed card
   - Example: a Queen is on top of the pile, and the drawn card is a 7.  7 is less than 12
3. Since the Ace is 1, it is divisible by all numbers, thus can always be placed

If a card does not meet the above criteria, it will be placed in the discard pile, face up.

During each pull from the deck, the player may discard a card if they choose.  This can be used as a strategy to play the more difficult cards.

The top card from the discard pile can also be played if a playable criteria is met.
- Example: played card is a Jack and drawn card is King.  King is discarded, but the next drawn card is Queen.  The King can then be retrieved from the top of the discard pile, provided there were no other discards that block the King.

After the initial deck is played through, the discard pile is then shuffled and played once.

# Winning
The player will aim for the following winning scenarios:

1. Perfect Game
   - A perfect game is when all cards have been played and there are no discarded cards
2. Prime Game
   - All prime cards have been played: 2, 3, 5, 7, Jacks (11), Kings (13)
3. Royal Party
   - All Kings, Queens, and Jacks have been played
4. Kings Company
   - All Kings have been played
5. Jack of all Trades
   - All Jacks have been played
6. Lucky 7's
   - All 7's have been played 
7. Average Win
   - The discard pile is less than 5

