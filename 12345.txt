class Weapon:
    def attack(self):
        print("primary attack")
class Sword(Weapon):
    def attack(self):
        print("slash")
class Bow(Weapon):
    def attack(self):
        print("xxx")
class character:
    def __init__(self, name, weapon):
        self.name = name
        self.weapon = weapon
    def fight(self):
        print("xxxxx")
hero=character("erenmen","verensword")
hero.fight()
