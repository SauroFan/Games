from Hero import Hero, Grut, Vlad, Yarik
import random as r

hero1 = Grut("Phantom Assasin", 50, 25, r.randint(15, 40), "Battle Fury")
hero2 = Hero("Tinker", 50, 50, 15, "Laser")
hero3 = Vlad("Pudge", 50, 25, 23, "Mask Of Madness")
hero4 = Yarik("Yarik", 50, 15, 10, "Bachok potik")

x = input("Select your hero: PA / Tinker / Pudge - ")
y = input("What you wwant to do? Fight / Hero info - ")
if y == "Fight":    
    if x == "PA":
        hero1.fight(hero2) 
    if x == "Pudge":    
        hero3.fight(hero2)
    if x == "Tinker":
        hero4.fight(hero3)
        
if y == "Hero info":
    hero1.print_info()
    hero2.print_info()
    hero3.print_info()
    hero4.print_info()
