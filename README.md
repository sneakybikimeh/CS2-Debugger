# CS2-Debugger
This debug.cfg file helps in the process of debugging CS2 commands when working on a config file.

# Installation
Open the archive and extract its content into the following path folder :

    "\...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\sound_player\"

Launch the game, then load the debug.cfg either through a config or by typing in the console the following command: "exec debugger.cfg".

Your game should play a sound upon config load, otherwise you must have a path issue and the file did not load correctly.

# Usage

Everytime you use the debugger alias, it will trigger a message feedback in the chat, and an echo in the console, then store the next debug message in memory.

If you want to use it in a static way, call the debugger[num] directly (the debugger alias will keep the last one used in memory for its next call).
