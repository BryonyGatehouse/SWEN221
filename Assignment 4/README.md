# Assignment 4 : The Card Game

The assignment is to create trick-taking card game. 

Part 1 - Card Comparisons
    -   Implement methods Card.equals(), Card.hasCode(), and Card.compareTo(). Latter method should sort cards by suit andrank, such that Hearts < Clubs < Diamonds < Spades.

Part 2 - Illegal Moves
    -   Implement the method Trick.play(Player, Card) to ensure that any attempt to play an invalid card, or to play out of sequence results in an IllegalMove exception being raised.

Part 3 - Cloning
    -   Replace/Override the method in AbstractCardGame with appropriate implementations in its subclasses so that it duplicates a game using deep clone rather than the given shallow clone method

Part 4 - Artificial Intelligence
    -   Implement the class 'SingleComputerPlayer' so it follows these rules:
        -   If the AI player can potentially win the trick, then it plays the highest eligible card
        -   If the AI player cannot win the trick, then it discards the lowest eligible card
        -   In the special case that the AI must win the trick, then it conservatively plays the least card needed to win
