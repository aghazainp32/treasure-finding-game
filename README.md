# treasure-finding-game
flow chat is givenprint('''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\` . "-._ /_______________|_______
|                   | |o;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''')
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.") 

#https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Treasure%20Island%20Conditional.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1oDe4ehjWZipYRsVfeAx2HyB7LCQ8_Fvi%26export%3Ddownload

#Write your code below this line👇
result=input('You are at a crossroad, where do you want to go? type "left" or "right"?\n').lower()
if result=="left":
  result2=input('you reach at the lack type "swim" to go throught the swiming or type "wait" if you want to go through the boat?\n').lower()
  if result2=="wait":
    result3=input('There is three door house? where do want to go type "red" for red type "blue" for blue & type "yellow" for yellow\n').lower()
    if result3=="yellow":
      print("congratulations you won the game")
    elif result3=="blue":
      print("eaten best by best game over")
    elif result3=="red":
      print("you burned by fire")
    else:
      print("game over")
  else:
    print("game is over before 2nd last stage")
else:
  print("Game is over")
  ![treasure](https://user-images.githubusercontent.com/107698416/175548500-35205b3f-ef5c-40f2-b322-7a411a35cbf9.png)


