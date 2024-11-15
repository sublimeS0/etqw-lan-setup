# ETQW LAN/Online w/ Custom Campaigns
Files and executables for custom campaigns in ETQW multiplayer

## Setup

1. Install the ETQW `.iso`. (This repo assumes you have obtained a legimiate copy of the ETQW legally).

2. Install the ETQW 1.5 patch found at https://www.splashdamage.com/games/enemy-territory-quake-wars/.

3. Copy contents of repo `base/` directory into local game root folder.

4. If hosting, copy `server-configs/` and `server-start-scripts/` into local game root folder.

5. Keep the Strogg hands off your oil.


## Start a LAN server

1. From the root directory, run `serverlauncher.exe`.

2. In the top left, go to *File > Open*.

3. In the file menu that opens, select a `.sprofile` from the `server-configs/` directory.

4. Make any desired to the rules.

5. Click *Start Server*.

The server will now show under the *Play on LAN* server list in game.


## Create your own campaigns

If you are here, you know documentation for custom ETQW content is somewhat lacking.. on the internet these days. I'll do my best to document what 
I've found here.


## Common Errors


- `failed to open log file 'demonware_server.log'`

Run server start file as admininstrator.