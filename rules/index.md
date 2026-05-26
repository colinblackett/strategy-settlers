# Strategy Settlers — Rules

A companion tool for the board game Settlers of Catan that replaces dice
rolls with predictable production based on board placement. Customize the
rules and eliminate random chance, shifting the focus completely to
strategy and diplomacy.

## The custom rules

Each turn, every player advances toward earning resources at a rate
determined by their board placements — measured by the dots under each
number tile. A settlement on a number with 5 dots gains 5/30 of a resource
each turn, so six turns later you're guaranteed one of that resource.
Combine multiple placements and your guaranteed yields stack. No dice, no
luck — just steady, predictable production.

Whenever a player places a settlement or city (including the initial
setup), tell the app how much their production increased — counted by the
dots under the number tiles, not the numbers themselves. The app then
shows what resources to expect on coming turns.

To help with resource collection, the app announces out loud at the start
of each turn:

- whose turn it is
- what resources each player receives on that turn

The players take the cards representing those resources from the bank and
then trade and spend them as usual.

### The robber

The robber is removed entirely — hex production can never be blocked.

### Soldiers

When any player plays a soldier, two things happen:

- any player (including the one who played the card) who has at that
  moment eight cards must halve their hand.
- the player who played the card can choose any other player and steal
  one of their cards.

## Optional rules

More house rules you can adopt to eliminate even more randomness:

### Development card reveal

Instead of having the development cards in a face-down deck, turn over the
first five cards in a row. The cards must be purchased in the order they
are displayed, but the players can see what card is for sale, and what
cards will follow. When a card is purchased, the other cards are moved
along (the front one becomes available) and another card is turned up at
the back of the five.

### Turn order auction

Instead of randomly determining the play order, it is determined by an
auction.

- the board is set up, with the number tiles in place, and the development
  cards for sale are revealed
- the players simultaneously determine which position they want in the
  turn order, each picking a position from 1 to N (N = number of players)
- the choices of the players are revealed, and can be tracked by putting a
  settlement token from each player in a line, clustering players that
  chose the same number, and leaving gaps for numbers that weren't chosen
- the players then take turns (in a randomly determined order)
- if the player is sharing their number with another player they must do
  one of the following:
  - move their token to a different number
  - choose any resource from the bank and add it as a bribe to a number
    no player has chosen
- if the player is not sharing their current number, they can either move
  to a different number or skip their turn
- Once all players are not sharing numbers, and every player's last action
  was to skip, the auction is over
- The players rearrange themselves at the table to reflect the resulting
  turn order, and any players on numbers with bribes take those bribe
  cards into their hand. These are combined with the normal starting cards
  the player gets during normal placement.

### Soldier timing

A player can play a soldier card at any point in their turn, including
after they have traded and/or spent cards to reduce their hand below the
limit.

### Victory point targets

We recommend playing to 12 points for a three player game, and 15 points for a two player game. 

## How to use the app

### 1. Players

Once play order has been determined, tap each color in the order players
will take turns. Tap again to remove a player. Use the `<  bank  >`
selector at the top to pick a voice (tap the middle of that strip to hear
a sample). When ready, tap "start game".

### 2. Initial production

As the players place their initial settlements, tap in their starting
production for each resource (by clicking the number in the column
corresponding to the resource). Use `<` and `>` to step between players.

Remember that production values come from counting the dots. A convenient
flow: wait until both of the player's settlements are placed, then for
each resource in turn, count the dots on the hexes adjacent to those
settlements and tap that total.

Tap "go" when initial setup is complete, and everyone's initial production
has been entered.

### 3. Play

Each turn the app announces whose turn it is and who gets what.

- Tap the **+** symbol (top-left quarter of the chart screen) to enter
  construction mode for the current player.
- Tap the **down-arrow** symbol (bottom half of the chart screen) when the
  player has finished trading and building, to advance to the next
  player's turn.
- If a mistake has been made (e.g. a settlement was placed but not
  tracked) tap the **up-arrow** symbol (top-right quarter of the chart
  screen) to revert to a previous turn.
- The top row of the chart shows every player's current total production
  rate.
- The remaining rows show the current and future turns:
  - whose turn it will be
  - what resources each player will receive on that turn

### 4. Construction

Whenever a player builds a new settlement or city, enter construction mode
on that player's turn, and enter the *increase* that they earned.

- If a settlement is placed, add the production dots for the (up to)
  three hexes around the new settlement.
- If a settlement is upgraded to a city, add the production dots for the
  increase. The settlement's production was already tracked, so the dots
  need to be added again once, to result in the city's 2x production.

---

Not affiliated with or endorsed by Catan Studio or Catan GmbH. CATAN and
Settlers of Catan are registered trademarks of Catan GmbH.
