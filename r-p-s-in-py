from random import randint

pls = 0
comps = 0
rounds = int(input("Enter the number of rounds you want to play: "))
game = 0

while True:
    pl = int(input("1.Stone 2.Paper 3.Scissor: "))
    comp = randint(1,3)

    if pl == comp:
        print("Tie")
        game = game + 1
    
    elif pl == 1:
        if comp == 2:
            print("You lose", comp , "beats" , pl)#IDK how does paper manage to do that.
            pls = pls - 1
            comps = comps + 1
            game = game + 1
            print("Scores are ", "Player: ",pls, "Computer: ",comps)
        else:
            print("You Win")
            pls = pls + 1
            comps = comps - 1
            game = game + 1
            print("Scores are ", "Player: ",pls, "Computer: ",comps)
    
    elif pl == 2:
        if comp == 3:
            print("You Lose", pl , "beats" , comp)
            pls = pls - 1
            comps = comps + 1
            game = game + 1
            print("Scores are ", "Player: ",pls, "Computer: ",comps)
        else:
            print("You Win")
            pls = pls + 1
            comps = comps - 1
            game = game + 1
            print("Scores are ", "Player: ",pls, "Computer: ",comps)
    
    elif pl == 3:
        if comp == '1':
            print("You Lose", comp , "beats" , pl)
            pls = pls - 1
            comps = comps + 1
            game = game + 1
            print("Scores are ", "Player: ",pls, "Computer: ",comps)
        else:
            print("You Win")
            pls = pls + 1
            comps = comps - 1
            game = game + 1
            print("Scores are ", "Player: ",pls, "Computer: ",comps)        
    
    if game == rounds:
        print("Gamer over")
        print("Final scores are:", "Player :",pls, " Computer: ",comps)
        if pls > comps:
            print("You Win")
            break
        elif pls == comps:
            print("Tie")
            break
        else:
            print("Try Again next time.")
            break
    else:
        print("Enter a number from 1 to 3")
        
    
    
