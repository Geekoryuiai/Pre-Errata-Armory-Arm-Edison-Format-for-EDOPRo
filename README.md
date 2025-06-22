Hello Duellist, thank you for downloading!


I noticed that Armory Arm lacked of its Pre-Errata version in EDOPro, which is very important for some old formats like Edison format, so I made it.

You will be able to play Armory Arm as printed in DP08, the very first print, according to Edison format's rulings (March 2010).
Pre-errata Armory Arm's trigger effect (inflicting damage equal to the ATK of a monster destroyed by battle by a monster equipped with Armory Arm) 
checked for the ATK of the destroyed monster right before leaving the field (and not in the GY).
This notably allows to make a very specific combo with Colossal Fighter that could be impossible if the effect checked the ATK in the GY.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

THE COMBO:

1)You control both Armory Arm and Colossal Fighter. Your opponent controls a monster with 1801 (onethousand-eighthundreds-ONE) or more ATK in ATK position 
(let's suppose there are no Warrior in GYs, which makes a 2800 ATK Colossal Fighter).

2)You equip Armory Arm to the opponent's ATK so it has more ATK than Colossal Fighter (Armory Arm gives it +1000 ATK when equipped).
You crash Colossal Fighter and take some battle damage. Colossal Fighter is of course destroyed by battle.

3)The monster your opponent controls destroyed Colossal Fighter, but you are the actual controller of Armory Arm, so you get to burn your opponent 
---> Armory Arm chain link 1 (mandatory trigger effect), Colossal Fighter chain link 2 (optional trigger effect).

4)At resolution, CL2 reborns Colossal Fighter and CL1 burns your opponent.
Both cards are not "once per turn" so you can keep going with this loop until you win, you just have to be sure you can get enough battle damage to keep the burn loop going without losing first.

Since Colossal Fighter can special summon itself from the GY during the said combo, it is not considered as the same card which was destroyed by battle anymore (it can in fact attack again) 
and it is not in the GY anymore, so checking its ATK in the GY at resolution would prevent the burn effect of Armory Arm.
That is why this errata is very important for Edison Format.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

HOW TO APPLY THE CHANGES:

In order to be able to play that version of Armory Arm, and so be able to experience actual Edison format mechanics and feelings, copy the downloaded files* in EDOPro folders as follows**:


1) Copy/move "cards-unofficial.cdb" file (in "database" folder) in ---> "...ProjectIgnis/expansions"

2) Copy/move "Whitelist 2010.03 Edison.lflist.conf" file (in "lflists" folder) into ---> "...ProjectIgnis/lflists"

3) Copy/move "29071342.png" file (in "pics" folder) into ---> ".../ProjectIgnis/pics"

4) Copy/move "c29071342.lua" file (in "script" folder) into ---> "...ProjectIgnis/script/pre-errata"

***

Have fun !

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Geekoyruiai
22.06.2025


* Keep a backup copy of these files if next updates will not implement an "official" Pre-Errata Armory Arm, so you can add it again!

** The folders' paths are indicated according to version 41.0.2 of EDOPro (as of the 22nd June 2025), they could change after updating.

*** Don't forget to select the "2010.03 Edison" banlist when building an Edison format deck, that will allow you to properly build the deck according to Edison format banlist and erratas. 
    If you do not want to select the banlist (N/A), do not forget to check "Alternate formats" checkbox in order to be able to see pre-errata cards and add them to your deck.
