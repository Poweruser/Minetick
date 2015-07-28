# Minetick

This is my mod of the popular [Craftbukkit Minecraft server](https://hub.spigotmc.org/stash/projects/SPIGOT/repos/craftbukkit/browse). It's main purpose is to increase the server's processing speed, by introducing multithreading and other optimizations. And while I'm at it, fixing bugs that I found. 

This repository covers the MinetickMod versions for Minecraft 1.8 and later. If you are looking for 1.7.x and earlier versions, check the repository [MinetickMod](https://github.com/Poweruser/MinetickMod).

### Compilation

MinetickMod has to be compiled with the [MinetickTools](https://github.com/Poweruser/MinetickTools/releases), which is an adapted version (specifically for this fork) of Spigot's BuildTools.
By default the latest version is selected for compilation, but with the `--rev` parameter you can compile these previous versions as well: `1.8.3`, `1.8.6`, `1.8.7`, `1.8.8`.      
Example command line: `java -jar MinetickTools.jar --rev 1.8.8`
