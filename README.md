# ai-research
Games for AI research.

Many of these games are Unity games, you can use [BepInEx](https://github.com/BepInEx/BepInEx/tree/v5.4.13) to help mod some of these games.

# Games without AI

### [Enter The Gungeon](https://store.steampowered.com/app/311690/Enter_the_Gungeon/)

A **singleplayer** roguelike procedurally generated dungeon solving game.

#### Mod tools
[ModTheGungeon](https://modthegungeon.eu/)

Mods/Plugins written in C#.

### [Mini Motorways](https://store.steampowered.com/app/1127500/Mini_Motorways/)

A **singleplayer** game that randomly generates the location of different houses and destinations in which the goal is to get a high score, Endless.
The game only requires the cursor to be used.

#### Modding 
[BetterMotorways](https://github.com/matias-kovero/BetterMotorways)
C#. Not a modloader, but can be modified in to an AI interface.

### [The Binding of Isaac Rebirth](https://store.steampowered.com/app/250900/The_Binding_of_Isaac_Rebirth/)

A roguelike **singleplayer** game in which the objective is to defeat monsters and bosses. 

#### Modding
https://moddingofisaac.com/
Not a modloader but instead you need to extract the mod into the game files, Moddingofisaac has tutorials on how to make a mod. This can be used to make a AI interface.

### [Beat Saber](https://store.steampowered.com/app/620980/Beat_Saber/)

A **singleplayer** **virtual reality** game where you have to hit boxes to the rythm of a song.\
You should use a custom Headset and Controller SteamVR drivers to emulate the hardware.\
Bonus points for using real hardware. :)

[Link to illustration](vrhardware.md)

#### Modding
[ModAssistant](https://github.com/Assistant/ModAssistant)

### [Super Tux](https://www.supertux.org/)

A **singleplayer** platformer game.

#### Modding
The game is open source.

### [DOOM Eternal](https://store.steampowered.com/app/782330/DOOM_Eternal/)

A **singleplayer** violent arcade first person shooter.

#### Modding

[eternalmods](https://wiki.eternalmods.com/)

### [Plague Inc](https://store.steampowered.com/app/246620/Plague_Inc_Evolved/)

A **singleplayer** game where the objective is to infect everyone.

### [Chromium BSU](https://chromium-bsu.sourceforge.io/)

A **singleplayer open source** video game where you have to shoot incoming enemy ships.

### Modding

It's open source.

### [King of the Hat](https://store.steampowered.com/app/837350/King_of_the_Hat/)

A **multiplayer** 2d party platformer game (which requires 2 players) where you fight with a hat (which is also your weakness)

### [Bad Time Simulator](https://jcw87.github.io/c2-sans-fight/)

A **singleplayer** game where the objective is to beat Sans (from Undertale) in a boss fight.\
[GitHub Source Code](https://github.com/jcw87/c2-sans-fight/)

### [Infectinator 3: Apocalypse](https://store.steampowered.com/app/666570/Infectonator_3_Apocalypse/)

A **singleplayer** fast paced simulation-strategy game.

May not work on Linux, it made my Gentoo Linux **unresponsive**.

# Games with a pre existing AI.

## Procedurally generated

### [Unrailed!](https://store.steampowered.com/app/1016920/Unrailed/)

A **singleplayer** game (which requires 2 players) where the objective is to build roads for the train to reach the destination.

#### Pre existing AI
[Unrailed AI](https://github.com/Flowtter/unrailed-ai)
[Demonstration](https://www.youtube.com/watch?v=Hu6cn4zaFlU)

However the pre existing AI for this game plays alongside a human and judging (judging done by human who knows little of the game) there is a large skill gap between the human and the AI. 

### [Crypt of the Necrodancer](https://store.steampowered.com/category/rogue_like_rogue_lite/)

A **singleplayer** roguelike rythmic dungeon game.

AI trained using only recorded human game-plays, described in Joonas Pussinen's Masters thesis. However, there is a large gap in AI performance and human performance for this game. (https://erepo.uef.fi/handle/123456789/24370)

#### Modding

Built in mod loader.

#### [Opensource clone](https://github.com/Zakru/opencrypt)
Open source version of the game.


## Not procedurally generated

### [supertuxkart](https://supertuxkart.net)

A **multiplayer** Game where the objective is to race other cars through the map.

#### Pre existing AI 

[SuperTux-AI](https://github.com/EZBUTD/SuperTux-AI)
