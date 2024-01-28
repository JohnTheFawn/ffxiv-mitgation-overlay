# ffxiv-mitigation-overlay
The purpose of this tool is to provide an alternative overlay focused only on tank mitigations.

Helps to separate the buffs into a separate area to make them easier to view and track.

The bars also offer a convenient way of estimating the time remaining without having to read any values.

Displays down to the 10ths of a second so you don't run into that weird mental state of "I don't know if the game is rounding up or down, I am afraid this is going to wear off .5s into it saying 1" or "Wow, that buff lasted for almost a whole second with no time left on the timer"

## Requirements and installation.

This is an addon for ACT, so [ACT itself is required](https://advancedcombattracker.com/download.php) and [must already be set up](https://github.com/ravahn/FFXIV_ACT_Plugin).

Inside of ACT, select the Plugins tab at the top, then the OverlayPlugin.dll tab.

Press New at the bottom, call it Mitigation Overlay (or whatever you want, dealer's choice), for the Preset choose "Custom" at the bottom.

In the URL field, paste in `https://johnthefawn.github.io/ffxiv-mitigation-overlay/`

Make sure "Enable Overlay" is checked

To help with sizing and position, I recommend turning "Force white background", resizing the window, and then turning off "Force white background" once you have it positioned how you want. After that, I turn on "Enable clickthrough" and "Lock overlay" so it doesn't prevent me from clicking on any parts of the UI or turning my camera in game.

![Image of Installation instructions](/readme_assets/installation.png)

## Screenshots

### Vanilla
![Gif of Final Fantasy 14 Icons and Addon Bars](/readme_assets/vanilla.gif)

### Addon
![Gif of Final Fantasy 14 Icons and Addon Bars](/readme_assets/bars.gif)

### Both
![Gif of Final Fantasy 14 Icons and Addon Bars](/readme_assets/both.gif)

### Dark Knight
![Gif of Final Fantasy 14 Dark Knight Mitigation Icons and Addon Bars](/readme_assets/drk.gif)

### Gun Breaker
![Gif of Final Fantasy 14 Gun Breaker Mitigation Icons and Addon Bars](/readme_assets/gnb.gif)

### Warrior
![Gif of Final Fantasy 14 Warrior Mitigation Icons and Addon Bars](/readme_assets/war.gif)

## F.A.Q

### Will this addon need to be updated when ACT or the game updates?

Nope! Well, incredibly infrequently. Everything is self contained. The only updates that will be required are when new mitigations are added to the game

Previous versions will continue to work just fine (except they won't display any new skills).

### Will this addon scale to my resolution?

Yup! Everything is programmed in a way to be responsive, just scale the area to whatever size you want and the bars will adjust accordingly

### Are those bars curved?

Sure are, they were the hardest part of the project, thanks for asking.

### Which jobs or skills are supported?

Currently every tank's personal and shared mitigation will work.

- Arm's Length
- Bloodwhetting
- Bulwark
- Camouflage
- Clarity of Corundum
- Dark Missionary
- Hallowed Ground
- Holmgang
- Holy Sheltron
- Heart of Corundum
- Heart of Light
- Living Dead
- Nebula
- Oblation
- Rampart
- Shadow Wall
- Stem the Flow
- Superbolide
- Vulnerability Down 
     - the mitigation provided by Warrior's "Vengeance", not to be confused with the thorns portion of the skill

