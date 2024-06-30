#gusse number 

import random
Rnum=random.randint(0,100)
print(Rnum)
while True:
    user=(input("Gusse the number or quit (Q) : "))
    if(user == "Q"):
        break
    user=int(user)
    if(Rnum == user):
        print(" You win the game !! ")
        break
    else:
        print("Try agin !!")
        if(Rnum < user):
            print("The number is bigger gusse small number ")
        else:
            print("The number is more small gusse the bigger number ")

print("-----GAME OVER------")
