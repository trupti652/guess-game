# guess-game
print("you have 3 chances to guess secret number,Try your luck😊 ")
serect_number=3
guess_count=0
guess_limit=4
while guess_count<guess_limit:
 guess_count+=1
 guess= int(input('guess:'))
 if guess==serect_number:
     print("you won!")
     break
 else:
     print("you lose!")

