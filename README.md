# So You Want To Mod No Man's Sky :rocket:
 
You saw this diamond in the rough of a game and thought: '*I wanna fix some of this shit.*'

Well, you came to the right place, space cowboy.
 
There's a lot of different resources on the subject. This is mostly a compilation + short explanation of those resources. A big part of modding is also doing research and figuring things out as you go along. Take the time to familiarize yourself with the files and tools that are a part of modding NMS, and join our [Discord chat](https://discord.gg/vRDWeFT), where you can always ask for help in figuring stuff out.
 
##1. NMS File Structure
**Nexus Mods** has a great introductory post about how the NMS file structure is put together, and how to get started with unpacking the files and making them suitable for modding:
http://www.nexusmods.com/nomanssky/news/12875/?



##2. How to **Unpack** and **Repack** your mod files:
The best way to get started is to fully unpack the whole game using Total Commander. You can 'run unpacked' (unpacking all the .pak files inside GAMEDATA/PCBANKS and run the game with loose files) or copy the unpacked files to another folder whilst continuing to run the game with .pak files only.

When unpacking everything for the first time, using Total Commander with the psarc plugin is recommended.

* Total Commander: http://nomansskymods.com/mods/total-commander-with-psarc-plugin/

* PSARC tool: http://nomansskymods.com/mods/psarc-decompile-tool/

* MBINCompiler: https://github.com/emoose/MBINCompiler

* Modspace: http://nomansskymods.com/mods/nms-modspace/

When creating mods, you'll quickly get used to the unpak, decompile, recompile, repak workflow, so here are some [quick instructions on how to un-PAK, un-MBIN, re-MBIN, and re-PAK files](https://www.reddit.com/r/NoMansSkyMods/comments/51kjk4/quick_instructions_on_how_to_unpak_unmbin_rembin/).

##3. Other **Tools** and **Goodies**:

* http://moddata.nmstep.com/

* http://nomansskymods.com/mods/categories/tools/

* http://www.nexusmods.com/nomanssky/mods/searchresults/?src_cat=5.



##4. Figure out what you want to work on!:

Once you have unpacked the game files, editing textures and sound files is relatively easy. More complicated stuff, you're looking at the **.exml** files decompiled by **MBINCompiler**. You want to go wild? Check out [NMSE](http://www.nexusmods.com/nomanssky/mods/9/?) and inject code right into the game itself. And the real magicians straight up hex edit **MBIN**s. If you have experience with disassembling and reverse engineering, checkout the [IDA named templates](http://nomansskymods.com/mods/ida-named-templates-i64/) and join our Discord `#mod-mbin` channel.




#TIPS AND TRICKS
 
### GENERAL
- When repacking files, make sure to preserve the game's unpacked directory structure.
- The current mod naming convention for paks is _MOD.ModderName.ModDescription.pak.
- You can click and drag files and folders you want to pack/compile/unpack/decompile to the executables of the tools. Alternatively you can set them in your PATH variable and call them through the commandline from anywhere.
- Check out the pinned posts and history on the relevant Discord chat channels. Usually there are links to the resources you need.


### TEXTURES
- When working on textures, save them in the **DXT5 ARGB** format, and make sure the file extension is in capital letters, **.DDS**.


### SOUND
Converting sound files back and forth is labour-intensive, so make sure to take a look at the resources you need:

* http://nomanswiki.ga/Replacing_Sound_Files

* http://nomansskymods.com/mods/audio-file-dump-renamed-reorganized-and-converted/

* https://www.youtube.com/watch?v=bxc40UDmaAg


### GAME SETTINGS
- The reverse-engineering work on the game is still on-going and not all **MBIN**s will decompile. If you feel like digging into the guts of the game, check out https://github.com/emoose/MBINCompiler/issues to see if there is anything you can help with. For relevant resources, check out the pinned posts on `#mod-mbin`.

***That's all for now. Go forth and mod!***


*Based on [@damanique](https://github.com/damanique)'s guide from [this](http://pastebin.com/N4aqLHzG) pastebin, with their permission. Feel free to contribute!*
