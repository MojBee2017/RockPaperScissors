# RockPaperScissors
play_game=True
while play_game:
    player1=input("Player 1:Rock,Paper,Scissors?: ")
    player2=input("Player 2:Rock,Paper,Scissors?: ")
    
    if player1.lower()=="rock" and player2.lower()=="scissors":
        print("Winner: Player1")
        
    elif player1.lower()=="rock" and player2.lower()=="paper":
        print("Winner: Player2")
    elif player1.lower()=="rock" and player2.lower()=="rock":
        print("It's a tie")
        
    elif player1.lower()=="paper" and player2.lower()=="scissors":
        print("Winner: Player2")
    elif player1.lower()=="paper" and player2.lower()=="rock":
        print("Winner: Payer1")
    elif player1.lower()=="paper" and player2.lower()=="paper":
        print("It's a tie")
    
    elif player1.lower()=="scissors" and player2.lower()=="scissors":
        print("It's a tie")
    elif player1.lower()=="scissors" and player2.lower()=="rock":
        print("Winner: Player 2")
    elif player1.lower()=="scissors" and player2.lower()=="paper":
        print("Winner: Player 1")
    else:
        print("Please response correctly")
   
    ask_it=input("Would you like to play another round? (Y/N)")
    while ask_it.lower() !="n" and ask_it.lower() !="y":
            ask_it=input("Would you like to play another round? (Y/N)")#raise Exception 
        
        
    if ask_it.lower()=="y":
            print("cool, lets go!")
    elif ask_it.lower()=="n":
            print("Byeee!")
            break
        
    not play_game
