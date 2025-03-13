Global Variables:
- additiontotal1
    - Holds the total of added cards in the add pile
- card number
    - Increments by 1 every time a card is rendered. Resets to 1 when re-rendering.
- Cards in Deck
    - Displays the amount of cards that are remaining in the deck.
- Color Choice
    - Holds the choice of color after playing a wild card
- color picked?
    - Tells the game a color has been chosen
- confirm Draw
    - The player actually clicked the deck and is drawing due to a +3 or +6
- Current Card
    - Displays the ID of the highest card in the Discard Pile
- Current Draw Count
    - If stacking +3s and +6s, this holds how many cards need to be drawn.
    - Related to Zieh
- Dran
    - Holds whose turn it is
- Karten S1
    - Holds the amount of cards player 1 has
- Karten S2
    - Holds the amount of cards player 2 has
- Karten S3
    - Holds the amount of cards player 3 has
- restriction
    - If you need to draw cards due to a + card being played
- SkipUsed
    - Holds if a skip was used or not
- Tres Called?
    - Has Tres been called? If not, 
- Turn Over?
    - Turn is over when high.
- Zeit
    - Displays time wasted
- Zieh
    - This is the visual variable that shows whenever stacking + cards.
    - Is just equal to f"+{Current Draw Count}"

Karten Variables:
- card
    - Variable used in clones to determine what card it is
- confirm add
    - All valid cards in addition spot are valid and can be added together
- local card number
    - unused variable :p
- nihm eins
    - unused variable :p
- redraw
    - the heck, another unused??
- seperationcardleng
    - Distance between the cards rendering on screen.

Text Variables:
- card
    - unused (this is VERY unoptimized...)
- confirm add
    - unused
- local card number
    - unused
- redraw
    - unused
- seperationcardleng
    - unused

Kartensatz
- card
    - unused
- confirm add
    - unused
- local card number
    - unused
- nihm eins
    - Which card # to pull from deck
        - The card deck isn't actually shuffled.. it's just defined on the spot which card you will get.
- redraw
    - unused
- seperationcardleng
    - unused

Color Picker Variables:
- clone count
    - holds the clone # 

Help Tips Variables:
- #
    - Clone ID
- tutorial active?
    - If the tutorial is active or not

CardNumber Variables:
- #
    - Clone ID

Gewinner Variables:
- #
    - Clone ID

Discard Pile Variables:
- starting card
    - First card on the Discard Pile

Lists:
- Cards in Deck
    - Contains what cards are currently present in the deck
- cards to add
    - Contains what cards will be added from the combine 3 feature
- DebugLog
    - Debug log, self explanitory
- Discarded Cards
    - Cards in the discard pile. If the Deck is empty, the cards from here go into the Cards in the Deck
- S1 + S2 + S3 Cards
    - Cards that each player holds