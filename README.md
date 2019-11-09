# Gamemaster's Alternative Fortress
Status: Alpha  
Version: v0.1.3  
Author: [Gamemaster](https://steamcommunity.com/id/gamemaster1379)  
Discord: https://discord.gg/NTxDN7K

This mod is currently in alpha. No weapons are final and concepts are subject to change at anytime.

## What is this mod?

This mod is a re-imagination of unlocks in TF2 through use of its attributes system. In short, it is a re-work of the unlocks in the game, rather than "fixing what is broken"

This mod is **not** a pro mode.

Pro modes focus on fixing what is "wrong" with a game and making it right. Typically, pro modes reduce a game to a very small subset of itself while keeping the same what competitive players deem correct.

That is not the focus of this mod. Instead, this mod focuses on accomplishing two things.

1) Leveling the playing field from veteran to newcomer.

This game has been out for 10 years. All of the unlocks, combos, and nuances in the game are all but second nature to a veteran. For someone who has not sunk thousands of hours into this game, the barrier to entry is much higher. This mode's goal is to change as many unlocks as possible (regardless of whether they are balanced or not) to something new to put everyone on equally uneven footing.

2) Exploring unused mechanics within the game files

Valve leaves a lot of clutter in their game files. In this instance, there are a lot of unused attributes that can introduce interesting dynamics never before seen in the game. Emphasis was made to make use of unused weapon attributes first.

### How it works

This mod is built upon asherkin's [tf2items](https://forums.alliedmods.net/showthread.php?t=115100) plugin, which runs on top of Sourcemod. The plugin strips out all attributes on all weapons in the server and sets new ones based on a configuration file


### Dependencies

- Team Fortress 2 server
- Sourcemod
- asherkin's tf2items plugin

## How do I use this?


### Setup

- Have Team Fortress 2 installed with a functioning Sourcemod plugin
- Download the latest release of Gamemaster's Alternative Fortress
- Merge the directories under "release" for your respective server type in the corresponding /tf/ directory

After setting up, restart the server. If the plugin is working correctly, tf2items should be listed in `sm plugins`. From there, check to see if all the weapons have their new listed attributes.

### Usage - Community

For community usage, all that needs to be done is have the plugin installed. After it's installed, you're all sets

### Usage - Competitive

For competitive usage, this plugin recognizes [RGL](rgl.gg) as the standard for 6v6 and 9v9 KOTH and Stopwatch. [ETF2L](http://etf2l.org/rules/configs/) is recognized for CTF and 5CP.

To usage in a competitive format, ensure the plugin is installed correctly.

Afterward, execute RGL configurations normally.

Once configs are executed, make sure to execute the whitelist provided with `rcon sm_whitelist_id gaf_whitelist_vXXX`

RGL configs do not unload custom plugins, so this will safely run through any RGL config executions. 

Soap DM may unload this plugin, so it is recommended to exempt this from any soap DM plugin unloading.



