# Project Gamma Drafting Card Game / Custom Cube

- *This information is a work in progress*
- Some information in this document may be inconsistent or outdated as the project is actively being worked on.
- Anything in {curly brackets} is a temporary name. The vocabulary is kind of a mess currently as the direction of the project remains uncertain.
- This project currently exists in a sort of limbo between it's own game and a custom cube with it's own cards and rules.
- Project Gamma is a temporary name. The project is being merged/using the world/setting of birdsandbees' tabletop rpg project.
- You can find the card design spreadsheet [here](https://docs.google.com/spreadsheets/d/1RDuqokq3RVDQv1vOBgSlnQbRpQ1KFyX1tBaPVvDhRUk/edit#gid=1942849584).
- This is likely going to be first and foremost focused on creating basically a cube for drafting, since then only one person needs to have the cards for multiple people to be able to play the game, which is particularly important considering this will end up just being a print and play thing.

Project Gamma is a drafting and deck building card game for 2-8 players with a focus on varied, open ended deckbuilding, player agency, and interactive back and forth gameplay. It can be played as either a cube draft or constructed with decks made by players before the game. It will feature 360 cards when finished, although if I feel like it I might make more cards.

In games you will play units and attack your opponent to reduce their life to 0 (starting at 20), but within this there is a lot of room for different strategies! The game is played in a dynamic shared round system, and seeks to reduce non-games to a minimum. You will look to leverage hidden information, tempo, and card advantage to overcome your opponent and win the game.

The game takes place in Atnia, the setting of birdsandbees' Tabletop RPG. A very short briefing on it is [here](https://docs.google.com/document/d/1G8hyoDu2zGPwW9QdNvyt99r06ejLt9ufbgVPVZVzGQ4/edit?usp=sharing). 

# Rules for playing the game:
### Shared Round
During each round players will take turns playing cards and taking actions. These actions include: Playing a card/ability, attacking, and passing.
- Pass - When both players pass, if cards are being played, all cards resolve, and if no cards are being played, move onto the next phase. Everything basically revolves around this double pass system, both players pass, then everything resolves and/or you move to the next step/phase.
- Playing a card/ability - To play a card or ability you pay it's cost at it's specified time and put it on the table, at which point priority passes to your opponent. Your opponent can then choose to take an action or pass. When both players pass, all cards currently being played are resolved from order of most recently played to first played. Costs are always payed immediately, and cards only do what they say when they resolve.
- Attacking - At {slow} speed during the main phase you may start an attack. Players can respond to this action just like cards and abilities, and when it resolves you will enter the combat phase. You may only attack once per round.

### Round Phases:
1 - beginning of turn ({unflip}, beginning step)
- {Unflip} all your cards in play.
- If a card refers to the start of the round, it happens here.

2 - Main phase
- Players take turns taking actions.

3 - End of turn
- Do end of turn things, then discard down to max hand size and start the next round.

### Combat:
Combat phase outline:
- Step 1 - Begin combat.
- Step 2 - Active player may either declare one or more attackers (moving combat to step 3), or pass. If a double pass occurs, move to step 4. Attacking player may only declare up to 3 groups of attackers per combat phase.
- Step 3 - Defending player declares up to one blocking unit for each attacking unit and passes (this may only be done once, and then the blockers are locked in). After combat step 3, move back to combat step 2.
- Step 4 - Damage. The attacking player is given priority. After a double pass occurs, all attacking units deal damage equal to their attack value to the defending player etc etc and move to step 5.
- Step 5 - End of combat.
Notes:
- Both attacking and blocking causes units to flip, and you cannot attack or block with flipped units.
- After combat, the game returns to the main phase and the player who was defending is given priority.

### Zones:
- Deck - Your deck of cards.
- Hand - Your hand.
- {In play} - All cards that are currently in play live here.
- Memory - When cards are destroyed or discarded, they go here.
- Void - 

### 5 different sources, or kinds of cards
they're going to be based off of something in birdsandbees' ttrpg world, so haven't decided on them yet. Edit: they're currently called sources.

### Card Types:
There are multiple card types:
- Unit - Units have offense and defense stats, and can attack or block.
- Claim - The first claim you play each round costs 0. All claims have "-> Flip: Add 1 resource of any of ~'s sources."
- Item - Items have a defense stat, and cost (1) less to play for each of your claims. 
- Spell - Spells do their thing on resolution, then are put into memory.
Any cards with these types may also may have sub types.

### Playing Cards:
Each card has a certain {speed}, indicating the time it can be played at. These will be printed on the cards as a symbol, similar to card types, and are not tied to any card type.
- normal speed cards that can only be played when you have priority during the main phase and no other cards or effects are on the stack
- {fast/flash/instant} speed cards may be played at any time you have priority.
- {response} speed cards can only be played while you have priority and something else is on the stack. (This is kind of necessary if we have activated abilities of things in play for example, to prevent you from being able to stall and pass priority all day waiting for your opponent to do something. Basically it's meaningful because there is a sort of priority economy when you have a shared turn, where you often want to wait to make your opponent make decisions first by making non committal actions.)
- Some effects may skip the stack, and happen immediately, they are denoted by ->

When you play a card, you pay it's cost and put it onto the stack. Your opponent is then given priority to respond. When both players pass, *all* cards and effects on the stack are resolved in first in last out order. To reiterate: you pay the cost when you play a card, and it does it's effect when it resolves. (When the last card/effect on the stack resolved, priority is passed to the player who did not start the stack. I'm not 100% on how to word this or all the ways in which it is relevant, but it essentially needs to exist because of how a shared round works. If you think about it in terms of magic, when you resolve a card for example a creature coming into play priority just goes to the active player (the person who's turn it is), but this obviously doesn't work with a shared round, the other person needs to get their turn to play.)

[Split card mockup](https://media.discordapp.net/attachments/836870887214284850/1149823439494987806/Delverer.png)
Many cards in project gamma are split cards, which can be played as one side or the other. Unless otherwise stated on the card, you cannot play both halves at once.

### Resource & draw system (this is the most important and original system):
- All cards in hand can be pitched/channeled into the channel pile/zone to produce 1 mana/resource of one of their realms (or any realm in the case of realmless cards).
- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 3, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- Players draw up to their maximum hand size.
- Note that channeling cards for mana does not use the stack (or whatever response system we end up with, but probably the stack), and cannot be responded to, however you may still only do it when you have priority.

### Starting claim:
When you construct your deck you also choose a starting {basic claim}. This claim will be added to your hand at the beginning of the game.

### Starting the game:
To start the game, randomly determine the first player. Each player then shuffles their deck, reveals their starting claim, and draws (maybe 6, maybe 8, this can be adjusted) cards, keeping 3 and putting the rest on the top and/or bottom of their deck in any order. After both players have finished drafting their hands, each player puts their starting claim into their hand. Now begin the first round of the game, priority starting with the first player as randomly determined. Each round, the player with the highest total power of their units is given priority first. If it is tied, priority begins with the player who played second in the previous round.

## Formats and ways to play the game:

These are all just potential ideas. All can be played in best 2/3 or best of one.
- Draft. It's cube draft.
- Constructed: 60 total cards, max 3x of each, 15 card sideboard.
- Highlander: 80 cards, max 1x of each, featuring the *super cool draft pool!* There will be a universal pool of ~30 cards, all realmless. This set of cards can rotate over time, perhaps weekly or monthly, hand picked and brand new cards selected for the pool. At the start of each match, shuffle the 30 card pool and create two {packs} of 10 (numbers not decided yet and must be tested) cards from the top, then draft 5 cards from those packs with your opponent. Do the same thing after game 1 and 2 (if you go to game 3) (no sideboarding) (you are required to put all the cards you draft into your deck) (this may have issues with claim count since you are changing the number of non claims, we'll have to figure a solution to that out later). 
- Mirror Format
- Experimental: fast cycle format. 20 cards, and you cycle through them

## Mirror Format:
Limited format for 2 players where you draft your cards for each round. Both players begin the game with an identical preconstructed deck of cards (one being the red deck and the other the blue deck). Different sources of resources don't exist in this format. Each deck is a kind of mini cube, with support for a variety of strategies.

Instead of drawing cards normally at the end of each round and start of the game, players draft cards. Also, in mirror format, cards are channeled face down rather than face up.

#### Ski Draft:
Both players take 10 cards from the top of their deck. Each player picks 1 card to keep, then passes the rest to their opponent. From pick 2 on, each pick players keep an additional card than the previous pick. Continue until all cards are drafted. Note: in this draft format, chosen/drafted cards are revealed as they are drafted.

- At the end of the round the following steps are carried out:
	- Each player may put any number of cards from their hand into their channel zone. The number of cards in a players hand and channel zone + 3, (up to 10) becomes that players' maximum hand size for the round round.
	- Each player puts all cards from their channel zone on the top and/or bottom of their deck in any order/combination
	- The draft is carried out, and all drafted cards are added to players hands. (Mirror format can be played with many draft formats, Ski Draft is recommended for players newer to the format, while [Hausman draft](https://luckypaper.co/resources/formats/housman-draft/) is worth trying at some point. Feel free to invent your own if you like.)
	- Players discard down (to the bottom of their deck) to their maximum hand size.

To begin the game, rather than drawing starting hands normally, start with a draft, with maximum hand size 5.
