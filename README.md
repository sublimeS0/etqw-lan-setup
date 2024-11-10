# ETQW LAN/Online w/ Custom Campaigns
Files and executables for custom campaigns in ETQW multiplayer

## Setup

1. Install the ETQW `.iso`. (This repo assumes you have obtained a legimiate copy of the ETQW legally).

2. Install the ETQW 1.5 patch found at https://www.splashdamage.com/games/enemy-territory-quake-wars/.

3. Copy contents of repo `base/` directory into local game root folder.

4. If hosting, copy `server-configs/` and `server-start-scripts/` into local game root folder.

5. Start the server by running the desired `.bat` file in `server-start-scripts/`.

6. Keep the Strogg hands off your oil.


## Start a LAN server

1. Select and run any of the server start batch files from `server-start-scripts/`. You may need to run as administrator.


## Create your own campaigns

If you are here, you know documentation for custom ETQW content is somewhat lacking.. on the internet these days. I'll do my best to document what 
I've found here.


## Common Errors


- `failed to open log file 'demonware_server.log'`

Run server start file as admininstrator.

- Campaign loads in select menu, but nothing happens when clicking play

Add contents of `base/def/` directory.