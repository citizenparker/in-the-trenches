# Power Lines (working title)

**Goal**: To build a line of cards extending from your base to the enemy base and dominate the enemy base. The first player to dominate the other player’s base wins. In event both players run out of cards, the winner is the player whose card is closest to the enemy base. (Note that this card need not be connected) If there is no closer player, the game is a draw.

## Anatomy of a Card

Each card has three parts: a value, a price, and an effect.

A card’s **value** represents how difficult it is for other cards to dominate this card. Higher values are stronger cards.

When a card has a positive **price**, you must discard that number of cards from your hand in order to play that card. When a card has a negative price, you _draw_ that number of cards from your deck in order to play it. If you cannot draw or discard the appropriate number of cards, you may not play the card.

Finally, each card has an **effect**. These vary from card to card and will generally be effects that take effect immediately, effects that persist as long as the card is in play, or effects that only trigger when some condition is true. Regardless, once a card is removed from play then any effects it triggered are over.

A **base** card serves as the player’s home base and has a value of 12. If you base is dominated by another player, you lose.

## Setup

Players place their base cards approximately 11 card lengths apart in an open play space. Each player then shuffles their deck and draws a hand of 8 cards from that deck. Randomly determine who goes first.

Starting with the first player, players alternate placing the card of their choice facedown but otherwise following the rules of placement (see below). Facedown cards are treated as value 5, cost 0 cards with no effect. When each player has played three such cards, the first player’s turn begins.

## Sequence of Play

On your turn, you have three actions. With one action you may:

* **Play a card** - First, pay the price of a card as described above. You may then play that card in the field such that it borders another friendly and is connected by friendlies to your home base.
* **Dominate a card** - Trash an enemy card whose value is two less than the total value of all friendlies bordering it. Friendlies which are disconnected from their base do not contribute to this total value.
* **Draw a card** - Draw one card from your deck

With two actions, you may:

* Shuffle your discard pile into your draw deck

**You may pass a turn and forfeit further actions for that turn only when there are no possible actions you can take. Reveal your hand to the other player to prove this is the case.** If all players pass the game in this fashion, the game is over.

## Terminology

* **bordering** - when a card touches another card. Cards may not significantly overlap.
* **playing a card** - paying a card’s price and then placing a card onto the play area so that it borders a friendly card. 
* **discard** - move a card to the discard pile of that player
* **trash** - remove that card from the game.
* **enemy** - any played card belonging to another player
* **friendly** - any played card belonging to the owner of the card.

## List of Cards
### Card / Price / Effect
* Base / - / Lose the game if this card is dominated, trashed, or discarded.
* 0 / 0 / The base value of this card is two less than the printed value of the highest bordering non-base friendly. If this card ever decreases in value, trash this card.
* 1 / -1 / Each friendly bordering this card has +1 value.
* 2 / -2 / If this card is trashed or discarded, the owner of the nearest enemy may choose an additional bordering friendly to discard. 
* 3 / -1 / Discard a friendly as an additional price to play this card.
* 4 / 0 / When an enemy is played that borders this card, draw a card.
* 5 / 0 / If this card is played such that it borders an enemy, randomly trash one card from an opponent’s discard pile.
* 6 / 0 / When playing this card, it may be played overlapping one enemy of equal or lesser value.
* 7 / 1 / When playing this card, you may dominate one bordering enemy as a free action.
* 8 / 1 / Each friendly bordering this card adds +1 to this card’s value.
* 9 / 2 / When playing this card, you may play another friendly bordering this card of value 5 or less as a free action.
* 10 / 2 / This is a ten. It has no other effect.

## Deckbuilding

Players can build their own deck from the cards listed above. The only rule is that a deck must be exactly 26 cards excluding the base card.

## Suggested Initial Deck
Card / Count
* 0  / 2
* 1  / 2
* 2  / 2
* 3  / 3
* 4  / 3
* 5  / 3
* 6  / 3
* 7  / 2
* 8  / 2
* 9  / 2
* 10 / 2

## FAQ

* Can facedown cards be discarded by other card effects?

> Yes. If this occurs, they go faceup into your discard pile like any other discard.
