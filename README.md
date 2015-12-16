# speed-mod

This is a mod for *The Binding of Isaac: Afterbirth* that:
* Removes the intro cutscene (cutscenes.xml)
* Removes all of the ending cutscenes, including the credits (cutscenes.xml)
* Removes all of the boss introduction cutscenes (versusscreen.anm2)
* Removes all of the floor transition cutscenes (nightmare1.anm2 to nightmare13.anm2)
* Removes the pedestal item pickup animation (001.000_player.anm2)
* Removes the jumping in the hole to the next floor animation (001.000_player.anm2)
* Sets the "shake" animation to 0 frames, which is the animation responsible for Book of Revelations, rainbow poop, black heart depletion, and so forth (giantbook.anm2)
* Slightly modifies the title screen (titlemenu.png)
* Sets boss death animations that are longer than 1 frame to 1 frame (except for Gabriel, Uriel, and Krampus)

So far, Monstro is the only boss that is actually done, I'll work on doing the rest later and remove this note.

Note that there is around 1 frame of lag whenever the shake animation is supposed to play (with the exception of entering or exiting Curse Rooms). I'm not sure how to fix this without the LUA API DLC.
