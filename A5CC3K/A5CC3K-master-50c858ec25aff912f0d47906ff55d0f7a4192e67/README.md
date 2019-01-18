# CC3K project
CC3K is an abbreviation for Chamber Crawler 3000 and is a command line game programmed with C++.
The goal of this game is to get the highest score possible. The score can be increased by earning golds throughout the game.
# Player races
s - shade, t - troll, d - drow, v - vampire, g - goblin.                                                      
The default player character race is a shade that has starting stats (125 HP, 25 Atk, 25 Def). However,
players have the option of choosing an alternate (but no less heroic) race: drow (150 HP, 25 Atk , 15 Def,
all potions have their effect magnified by 1.5), vampire (50 HP, 25 Atk, 25 Def, gains 5 HP every successful
attack and has no maximum HP), troll (120 HP, 25 Atk, 15 Def, regains 5 HP every turn; HP is capped at
120 HP), and goblin (110 HP, 15 Atk, 20 Def, steals 5 gold from every slain enemy).
# Enemy races
(H)uman, d(W)arf, (E)lf, (O)rc, (M)erchant, (D)ragon, Half(L)ing.                               
Human (140 HP, 20 Atk, 20 Def, drops 2 normal piles of gold), Dwarf (100 HP, 20
Atk, 30 Def, Vampires are allergic to dwarves and lose 5HP rather than gain), Elf (140 HP, 30 Atk, 10 Def,
gets two attacks against every race except drow), Orcs (180 HP, 30 Atk, 25 Def, does 50% more damage to
goblins), Merchant (30 HP, 70 Atk, 5 Def), Dragon (150 HP, 20 Atk, 20 Def, always guards a treasure hoard),
and Halfling (100 HP, 15 Atk, 20 Def, has a 50% chance to cause the player character to miss in combat, i.e.
takes priority over player character's ability to never miss).
# How to move
ea - player goes East, we - player goes West, so - player goes South, no - player goes North
# Items(Potions)
Restore health (RH): restore up to 10 HP (cannot exceed maximum prescribed by race)                                                      Boost Atk (BA): increase ATK by 5                                                                                                           Boost Def (BD): increase Def by 5                                                                                                    Negative Potions:                                                                                                                      Poison health (PH): lose up to 10 HP (cannot fall below 0 HP)                                                                            Wound Atk (WA): decrease Atk by 5                                                                                                       Wound Def (WD): decrease Def by 5


