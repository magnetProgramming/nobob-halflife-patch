# nobob-halflife-patch
A simple client.dll patch that removes the main forward/backward view bobbing in Half-Life.

I started replaying Half-Life and could barely last 10 minutes before motion sickness kicked in. None of the launch options or mods helped, so I patched the client.dll myself. This removes the big “main” bob. The small side-to-side sway is still there for now, but I might patch that later.

I couldn’t find any existing patch that does this, so here it is.

## Installation

**0.** Back up your original `client.dll` in case you want to revert.

**1.** Replace the file here with the patched version:

SteamLibrary\steamapps\common\Half-Life\valve\cl_dlls\

**2.** Launch the game. The main view bobbing should now be gone.

if you have any problems email me at magnet.magnetic448@passfwd.com
