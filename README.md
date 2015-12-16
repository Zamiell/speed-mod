# speed-mod

This is a mod for *The Binding of Isaac: Afterbirth* that:
* Removes the intro cutscene (cutscenes.xml)
* Removes all of the ending cutscenes, including the credits (cutscenes.xml)
* Removes all of the boss introduction cutscenes (versusscreen.anm2)
* Removes all of the floor transition cutscenes (nightmare1.anm2 to nightmare13.anm2)
* Removes the pedestal item pickup animation (001.000_player.anm2)
* Removes the jumping in the hole to the next floor animation (001.000_player.anm2)
* Sets the "shake" animation to 0 frames, which is the animation responsible for Book of Revelations, rainbow poop, black heart depletion, and so forth (giantbook.anm2)
* Removes the Monstro death animation (020.000_monstro.anm2)
* Slightly modifies the title screen (titlemenu.png)

Note that there is 1 frame of lag whenever the shake animation is supposed to play (with the exception of entering or exiting Curse Rooms). I'm not sure how to fix this without the LUA API DLC.
