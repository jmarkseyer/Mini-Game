# Mini-Game
Minecraft Mini Game.
print(r'''
           ,@@@@@@@,
       ,,,.   ,@@@@@@/@@,  .oo8888o.
    ,&%%&%&&%,@@@@@/@@@@@@,8888\88/8o
   ,%&\%&&%&&%,@@@\@@@/@@@88\88888/88'
   %&&%&%&/%&&%@@\@@/ /@@@88888\88888'
   %&&%/ %&%%&&@@\ V /@@' `88\8 `/88'
   `&%\ ` /%&'    |.|        \ '|8'
       |o|        | |         | |
       |.|        | |         | |
jgs \\/ ._\//_/__/  ,\_//__\\/.  \_//__/_
''')
print("Minecraft Mini-Quest: The Cave of Choices")
print("Choose your answer wisely. Good luck and have fun!")

import time
import sys

path = input("You're mining deep underground and find two tunnels. One leads left, the other right. \n(Choices: Left or Right)\n").lower()
# 1st scene
if path == "left":
    print("A creeper sneaks up and explodes.💥Game Over!")
    time.sleep(1)
    sys.exit()
elif path == "right":
    print("You find a hidden underground village with villagers.")
else:
    print("You wander aimlessly, punching trees in the dark...")
    time.sleep(2)
    print("Suddenly, Herobrine appears and your screen goes black.")
    time.sleep(1)
    print("💀 Game Over. No one will believe what you saw.")
    sys.exit()
# 2nd scene
the_offer = input("A villager offers you a suspicious stew.Do you drink it or refuse? \n(Choices: Drink or Refuse)\n").lower()
time.sleep(2)
if the_offer == "drink":
    print("You get nausea and faint in the cave.💀 Game Over")
    time.sleep(2)
    sys.exit()
elif the_offer == "refuse":
    print("The villager nods and hands you a diamond pickaxe instead.")
else:
    print("You wander aimlessly, punching trees in the dark...")
    time.sleep(2)
    print("Suddenly, Herobrine appears and your screen goes black.")
    time.sleep(1)
    print("💀 Game Over. No one will believe what you saw.")
    sys.exit()
# 3rd scene
bedrock = input("With the pickaxe, you discover a bedrock door with a strange glow.Do you open it or leave? \n(Choices: Open or Leave)\n").lower()
time.sleep(2)
if bedrock == "open":
    print("You find a room filled with enchanted gear and diamonds.🏆 You Win!")
    time.sleep(2)
elif  bedrock == "leave":
    print("You return to the surface safely, but empty-handed.😐 Neutral Ending")
    time.sleep(1)

else:
        print("You wander aimlessly, punching trees in the dark...")
        time.sleep(2)
        print("Suddenly, Herobrine appears and your screen goes black.")
        time.sleep(1)
        print("💀 Game Over. No one will believe what you saw.")
