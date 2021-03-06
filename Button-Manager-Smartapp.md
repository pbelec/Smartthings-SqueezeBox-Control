# **Smartapp Squeezebox Button Manager**

The Squeezebox Button Manager is an optional smartapp to associate virtual momentary buttons with player functions. This allows for control of player(s) by voice or routine automations.  To keep it simple, buttons must already be existing to be used in the smartapp.

Install a copy of it for each player that needs voice and/or automation control.

Create a **momentary button** for each function you want to implement for each player.  Momentary was used, since there was no "off" side of these functions, and it keeps it cleaner, since the current state of the player does not have to be kept in sync this way.

Simply select the player to control and select the appropriate virtual button with each desired player function.  Give it a name for future reference, save it and you should be good to go. 

There are currently 6 player functions implemented.  Feel free to request additional, no promises though.

play
pause
stop
preset button 1
preset button 2
preset button 3


None of the functions are required to be associated with a button, but you obviously are going to set up at least one if you are using the smartapp.

By using distinct names and Google Assistant shortcuts/routines, (sorry I dont' speak Alexa), easy voice control is available.  For example, "pause Boom", sould pause my Boom player, or "jazz on pi" would start playing the jazz genre on my piCore if i had associated that with a preset. Turning on a button in a Smarthings routine would easily include that player function in it, such as starting your morning music with your Good Morning routine.

See player-preset document for how to set those buttons up in the player.



