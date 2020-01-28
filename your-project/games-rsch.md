# Game Options



## Strong Random Password Generator
* 

## Guess The Number
*

## Hangman
* 

## Message Encryption & Decryption
* 

## Mastermind
* 

## Tic Tac Toe
* 

## Blackjack
* #### Before Starting the game:
   -  Deck
   -     * 1 standard deck of 52 cards
              * 4 suits (Spades, Hearts, Clubs, Diamonds); 13 cards/suit
   -  Facevalue 
   -          * Picture cards: 10 value/cd; eg. Kings, Queens, and Jacks;
              * Aces: either 1 or 11;
              * Rest: face value.
* #### Game Goal: 
   -  Get to 21 points closer than the dealer does without going over  
   -     * "Soft Hand":
           * Because Ace can be either 1 or 11, this creates a softhand.
           * ie. if the player has a 4 and an Ace, the player has a soft 15 
                   -- meaning, the points can be either 5 or 15
           * Facevalue is always perceived however which favors the player
         * "Hard Hand" is when there is no ambiguity of facevalue
   -     *"Blackjack" / "Natural":
            *Get 21 points on the player's first two cards
         *"Busted" / "Busting":
            *if dealer or player by drawing more cards gets their points more than 21
* #### Shoe game
   -  a type of Blackjack games
   -     * a "Shoe", is the device on dealer's left hand side from which dealer draws cards from; 
              * a "Shoe" holds 6 -8 decks of cards
              * for the sake of this project, only 1 deck will be used
              * Single deck Shoe game
                  * "Insurance" will not be considered in this game either
         * a "Check", is the gaming chip which holds monetary value in a game for players to "bet"
           - Minimum bet: $5
           - Maximum bet: $500
           
| Game flow: |
|:----------:|
   * Walk up to table --> dealder greets player --> Whether to participate in gambling
       -    N ( Kudos. Have a healthy life )
       -    Y ( 1.Decides the amount to spend; 2.Exchanges currency for checks )
* Place checks of desired amount in betting circle. Game Starts.
* Dealer draws 2 cards to player --> dealer gets 1 card facing up and 1 card facing down
* Players has 3 options after receiving 2 cards:
    - --> Staying: "I want to stay."
    -       * player will not receive another card and do nothing before current round ends
            * ie. if player's first 2 cards equals 17 through 21, then the player is recommended to "stay"
    - --> Hitting: "I want to hit."
    -       * player will receive another card, additing to the total facevalue
            * player is allowed to keep "hitting" until total facevalue reaches 18 thorugh 21 
                    OR until player "busts"
            * ie. if player's first 2 cards equals 2 through 16, then the player is recommended to "hit"     
    - --> Doubling Down: "I want to double down."
    -       * player will only receive one card, additing to the total facevalue
            * bet of an equal or lesser amount 
                  * if player wins, player gets paid for both of bets
                  * if player loses, player loses both of bets
            * "Odd Moves": 
                  * if player decides to double down for less than the original bet
                        *"Odd, dealer will be watching you, but it's okay."
                  * if player decides to double down when facevalue of first 2 cards is 12 or greater
                        *"Are you wasted? Or are you trying to cheat?"
    - --> Splitting: "I want to split."                  
    -       * player splits 2 cards into 2 seperate hands of 1 card
            * player must bet at the same amount as original bet 
            * ie. if player's first 2 cards are the same facevalue, then the player may choose to "split"  
            * --> player can choose to play double-down or to split again
            BUT! player can only play one hand at a time
                  * to split again, player must receive another card at the same facevalue
                          * most cards can be split up to 3 times -- > gives player four hands total
                          * splitting Aces will only receive 1 card --> Hence, Ace cannot be further split 
                              * it's not a Blackjack, if player received a 10 after spliting Aces
    - --> Surrender: "I want to surrender."                  
    -       * player takes an automatic loss after receiving the original 2 cards
            * player loses half of bet instead of all 
            * ie. if player has a hard 16 while dealer has a 10 up card
                --> player might want to surrender to prevent from losing the entire bet
            * surrender can only happen on the first 2 cards; cannot surrender after having "hit" already
            
* Dealer's Rule:
    -       * dealer always has to hit when facevalue is 16 and lower;
            * dealer must stay when facevalue is 17 through 21;
            * if dealer goes over 21, dealer "busts", player wins
* When dealer is done with their turn
    -    player compares their facevalue against dealer's
    -    whoever's is closer to 21 wins the hand
    -       * if dealer wins: dealer takes the bet
                -> if dealer hits Blackjack, player automatically loses all bet
            *if hands are the same: "Push", and money will stay
            * if player wins: dealer pays players' bet 1 to 1 
                -> if player's first 2 cards are a Blackjack, player wins automatically and gets paid
                      * Blackjack offer is 3 to 2, player gets 1.5 times original bet
                      * ie. player bet $10 --> Blackjack --> player gets paid $15
                   --> if dealer also gets Blackjack, then it's a "Push", money will stay put 
        
          
## Soldier & Dice (Risk)
*
