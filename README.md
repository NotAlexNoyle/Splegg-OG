# Splegg-OG

![Icon](https://raw.githubusercontent.com/NotAlexNoyle/Splegg-OG/master/assets/splegg-logo.png)

**Splegg-OG** is a Splegg plugin originally made by MrLuangamer, updated for Worldedit 7.2 and Spigot 1.16.4 by Hraponssi, then updated for Purpur 1.18.2 for use by [TrueOG](https://true-og.net/) by [NotAlexNoyle](https://github.com/NotAlexNoyle/).

Dependencies: WorldEdit, Vault.

**To Set Up:**:

`/splegg create my-map` First, create a Splegg map with a name of your choosing.

`/splegg setspawn my-map` The amount of spawn points you set is the amount of players that will be able to join the map.

`/splegg setspawn my-map next` You can define new spawn points for a map with or without the "next" keyword.

`/splegg setspawn my-map 3` At any time, you can modify existing spawn points by using the number of the order in which you created them.

`/splegg setlobby my-map` Set a lobby area for the map during the voting/warm-up period.

`//wand` Summon a wand with WorldEdit and then use it to select two points. These represent the corners of your floor.

`/splegg addfloor my-map` Add the area you just selected with WorldEdit as a floor. You can add as many as you like.

`/splegg join my-map` You can now join the map you just created, and so can anyone else with splegg.join permission.

`/splegg start` Anyone with splegg.admin permissions can start the game even if less players join than there are spawn points.

[Original Bukkit Page](https://dev.bukkit.org/projects/splegg-minigame).

*The current Gradle build target is Purpur 1.18.2*

**To Build:**

`./gradlew build`

The resulting .jar file will be in build/libs/

**Known Bugs:**

- Shovel is given in lobby sometimes

- Splegg Shop is incomplete

- Dying or leaving a game teleports players to the wrong point

- "you are already playing" message is sometimes displayed even after leaving

- pre-game inventory is not always being preserved

- right clicking blocks shoots two eggs when it shouldn't

- The shooting sound is wrong

**Licensed under the GPLv3.**