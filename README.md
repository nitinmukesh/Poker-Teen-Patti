# Poker(Teen Patti)
This project determines the winner from array of cards

H- Heart, S - Spades,C - Clubs, D - Diamonds
A - Ace, Q - Queen, K - King, J - Jack

# Rules :
Ranking of the cards from Highest to lowest -
1. Same Number (Same Number of different colous Eg : (highest)'AH','AS','AC' ... '2H','2S','2C'(lowest))
2. Pure sequence,(Sequence with same colour Eg : 'QH','KH','AH'...'2H','3H','4H')
3. Sequence (or run),(sequence with different colour Eg : 'QH','KS','AD'.....'2H','2C','2D')
4. Color,(Same colour Eg : 'AH','QH','JH'... '2H','3H','5H')
5. Pair (two cards of same rank Eg : 'AH','AD','KD' ... '2H','2H','3D')
6. High Card.('AH','KH','JD'....'2H','3D','5S')

For the below example : 
Player - 0,2,4 ---- Rank 5 (Pair)
Player - 1 ---- Rank 3(Sequence)
Player - 3 ----- Rank 6 (High Card)
So the winner is Player - 1

var input = [

    ['2H','2S','3C'],
    ['3H','4H','5S'],
    ['KS','KS','JH'],
    ['6H','10H','AD'],
    ['AS','AD','2S']
    
    ];
    
 
