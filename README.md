import random
l={1:"Rock",2:"Paper",3:"Scissors"}
i=random.randint(1,3)
print("1:Rock,2:Paper,3:Scissors")
a=int(input("\nKindly enter your choice by its number equivalent: "))
print("Your choice: ",l[a],"\nComputer choice: ",l[i])
if(i==1 and a==3):
    print("Computer Wins")
elif(i==a):
    print("Draw")
elif(i==2 and a==1):
    print("Computer Wins")
elif(i==3 and a==2):
    print("Computer Wins")
else:
    print("Player Wins")
