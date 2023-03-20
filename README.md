# bad-Python-games
import random


player = input("Enter anything to to play:")


low1 = 1
high1 = 6





slot1 = random.randint(low1, high1)
print(slot1)

low2 = 1
high2 = 6



slot2 = random.randint(low2, high2)
print(slot2)

low3 = 1
high3 = 6



slot3 = random.randint(low3, high3)
print(slot3)

if slot1 == 1 and slot2 == 1 and slot3 == 1:
 print("Jackpot!")

 if slot1 == 2 and slot2 == 2 and slot3 == 2:
  print("Jackpot!")

 if slot1 == 3 and slot2 == 3 and slot3 == 3:
  print("Jackpot!")

 if slot1 == 4 and slot2 == 4 and slot3 == 4:
  print("Jackpot!")

 if slot1 == 5 and slot2 == 5 and slot3 == 5:
  print("Jackpot!")

 if slot1 == 6 and slot2 == 6 and slot3 == 6:
  print("Jackpot!")

else:
  print("No Jackpot")













