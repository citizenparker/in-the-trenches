# Power Lines (working title)

**Goal**: To build a line of cards extending from your base to the enemy base and dominate the enemy base. The first player to dominate the other player’s base wins. In event both players run out of cards, the winner is the player whose card is closest to the enemy base. If there is no closer player, the game is a draw.

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
* **Dominate a card** - Trash an enemy card whose value is three less than the total value of all friendlies bordering it. If this causes any enemies to be disconnected from their base, draw a card.
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
0 / 0 / The base value of this card is two less than the printed value of the highest bordering friendly. If this card ever decreases in value, trash this card.
1 / -1 / Each friendly bordering this card has +1 value for the purposes of resisting domination.
2 / -2 / If this card is trashed or discarded, the owner of the nearest enemy may choose an additional bordering friendly to trash. 
3 / -1 / Discard a friendly as an additional price to play this card.
4 / 0 / When an enemy is played that borders this card, draw a card.
5 / 0 / When you are able to dominate an enemy this card borders, you take an action to swap the enemy with another enemy of that player. If you do so, trash this card.
6 / 0 / No player may play more than one friendly or enemy bordering this card during a turn.
7 / 1 / When playing this card, you may dominate one bordering enemy as a free action.
8 / 1 / Each friendly bordering this card adds +1 to this card’s value.
9 / 2 / When playing this card, you may play another friendly bordering this card of value 5 or less as a free action.
10 / 2 / Enemies bordering this card are not considered connected to their owner’s base.

## Deckbuilding

Players can build their own deck from the cards listed above. The only rule is that a deck must be exactly 30 cards.