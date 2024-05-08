# C4rdC0unting Requirements
c4rdC0unting is an application intended to teach users how to count cards in a game of Blackjack in order to increase their chances of winning. This will be done by simulating a game of Blackjack for practice.
## Functional Requirements
1. The game should be designed to test a users ability to count cards in the following manner:
    1. The game will keep track of the current count according to the following policy pertaining to the value of each revealed card:
        - 2-6 -> +1
        - 7-9 -> 0
        - 10-A -> -1
    2. The game will prompt the user to recall and input the current count at regular intervals based on a selected difficulty. Difficulties include:
        - Beginner - One deck, check count every 13 cards.
        - Intermediate - Two decks, check count every 26 cards.
        - Advanced - Four decks, check count every 52 cards.
        - Expert - Six decks, check count every 78 cards.
    3. The number of decks in a game will also depend on the difficulty chosen as shown abaove.
    4. The game may support the adittion of betting simulation in a future iteration to instruct users when or when not to bet based on the count of the game