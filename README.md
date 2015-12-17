# speed-mod v1.1

This is a mod for *The Binding of Isaac: Afterbirth* that:
* Adds a small logo to the title screen (titlemenu.png)
* Removes the intro cutscene (cutscenes.xml)
* Removes all of the ending cutscenes, including the credits (cutscenes.xml)
* Removes all of the boss introduction cutscenes (versusscreen.anm2)
* Removes all of the floor transition cutscenes (nightmare1.anm2 to nightmare13.anm2)
* Reduces the the pedestal item pickup animation from 42 to 17 frames (001.000_player.anm2)
* Removes teleport animations (001.000_player.anm2)
* Removes the fetal position animation at the beginning of every floor (001.000_player.anm2)
* Reduces the jumping in the hole to the next floor animation from 16 to 2 (001.000_player.anm2)
* Removes the beam of light animation when going to the Cathedral (001.000_player.anm2)
* Removes the big chest enter animation when going to The Chest or beating the game (005.340_big chest.anm2)
* Sets the "shake" animation to 0 frames, which is the animation responsible for Book of Revelations, rainbow poop, black heart depletion, and so forth (giantbook.anm2 + giantbook_eternalheart.anm2)
* Sets boss death animations that are longer than 1 frame to 1 frame (except for Krampus, Uriel, and Gabriel)

Notes:
* Pedestal item pickups were set to 17 frames since there is only 17 frames of actual animation. Removing the animation entirely makes the game feel a little off.
* The lowest frame count that the jumping in the hole animation can be set to is 2. Otherwise, the game will soft-lock when the player jumps into a big chest.
* There is around 1 frame of lag whenever the shake animation is supposed to play (with the exception of entering or exiting Curse Rooms). I'm not sure how to fix this without the LUA API DLC. However, this isn't really a major issue.
