# speed-mod v1.2

This is a racing mod for *The Binding of Isaac: Afterbirth* that removes cutscenes and some useless animations. Since it is only a "graphics" mod, it influences the game in only very minor ways, so you can combine it with whatever other mods you want.

[Download the latest verion here](https://github.com/Zamiell/speed-mod/releases).

## How It Impacts The Game
From a strategic standpoint, hardly anything is changed. Here's a small list of things that are:

* Betrayal is now a take. You can also use it to lock in devil deals if needed.
* Dry Baby is now always a take.
* You might not want to bomb out of certain boss rooms that you normally do. For example, Monstro II has a long death animation and most racers bomb out of his room on The Cathedral. But now, if you have high DPS, you might not want to waste the bomb.


## Full List of Changes
* Adds a small logo to the title screen (titlemenu.png)
* Removes the intro cutscene (cutscenes.xml)
* Removes all of the ending cutscenes, including the credits (cutscenes.xml)
* Removes all of the boss introduction cutscenes (versusscreen.anm2)
* Removes all of the floor transition cutscenes (nightmare1.anm2 to nightmare13.anm2)
* Removes the fetal position animation at the beginning of every floor (001.000_player.anm2)
* Reduces the jumping in the hole to the next floor animation from 16 to 2 frames (001.000_player.anm2)
* Removes the beam of light animation when going to the Cathedral (001.000_player.anm2)
* Removes the chest entering animation when going to The Chest or beating the game (005.340_big chest.anm2)
* Sets the "shake" animation to 0 frames, which is the animation responsible for Book of Revelations, rainbow poop, black heart depletion, and so forth (giantbook.anm2 + giantbook_eternalheart.anm2)
* Sets boss death animations that are longer than 1 frame to 1 frame (except for Krampus, Uriel, and Gabriel)

## Other Notes
* The lowest frame count that the jumping in the hole animation can be set to is 2. Otherwise, the game will soft-lock when the player jumps into a big chest.
* There is around 1 frame of lag whenever the shake animation is supposed to play (with the exception of entering or exiting Curse Rooms). I'm not sure how to fix this without the Afterbirth+ API. However, this isn't really a major issue.
