# A3DSOverthrow

What is this?

Arma 3 Dedicated server Overthrow Template (Batch)
Why make something so simple, well actually to kind of test Github functonality and help out some Server Owners hopefully.

I saw really few Overthrow servers, so I thought i'd add a template for server owners, making it easier and quicker to setup your Overthrow server. These batch scripts doesn't include any restart script. [BEC](http://ibattle.org/) does this. (Not included)

# Installation

1. Installation: Install ArmA 3 Dedicated server from either your Steam client, or [SteamCMD](https://steamcdn-a.akamaihd.net/client/installer/steamcmd.zip)

2. Download [ACE](https://github.com/acemod/ACE3/releases/latest) and [Overthrow](https://github.com/ArmaOverthrow/Overthrow/releases/latest), place them in your Arma 3 Server folder.

3. Copy "Starters" and "Overthrow" in root of the Arma 3 server folder. (Where arma3server_x64.exe is located)


# Batch Scripts

A3DS.bat (Normal server start with realtime priority) <- Use this if you don't need any HC's.

#HC found under Starters\Remote HC <- Use this if you need HC's on the same computer as the server.

#HC1 (# means affinity according the to the CPU, so it would be HC1 = CPU 1. Server = CPU 0.)

#HC2 (# means affinity according the to the CPU, so it would be HC2 = CPU 2.)

#HC3 (# means affinity according the to the CPU, so it would be HC3 = CPU 3.)


Dedicated HC (Multiple dedicated HC PC's)



# Default settings and editing

Server name: `Overthrow version v0.7.5.3 hosted by Github;` change this in (Overthrow/Server.cfg)

Remember to add your IP's for your dedicated HC machines if needed (This is not needed for if you are using the same machine for both server and HC's.)

Admin login password #login : !123

BattlEye RCON password: !123 (Overthrow\BattlEye\BEServer_x64.cfg)

Difficulty setting: Overthrow recomended, taken from their wiki page. http://wiki.armaoverthrow.com/wiki/How_to_run_a_dedicated_server

I have included batch scripts for using HC's on another computer/server. Write down your #IP in the folder (Starters/Remote HC/HC#.bat)


# Alot of kudos to the Overthrow dev team! Much love brederen!

# Bonus
[Songs to Overthrow to](https://www.youtube.com/playlist?list=PLUrzXEa-EVEfOuskTrGAqQK3UUpoUDgrJ)

[Official Discord](https://discord.gg/w3JDQnX)
