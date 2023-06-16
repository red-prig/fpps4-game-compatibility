fpPS4 game compatibility
  
Anyone is free to update or share their results here, with the following requirements:

-   You  **must**  use an official trunk branch builds. You can try main branch but it it pretty old and should be used if game has serious emulation bugs - except an unimplemented functions - there none regressions with that part, if some game does not work with main branch due an unimplemented functions it won't work with trunk branch either with trunk branch. All mods & cheats of any kind must be disabled.
-   Include the title ID in all caps in the title of the issue; i.e. issue name will be Disco Elysium: The Final Cut - CUSA26506 or you may see existing issues for examples.
-   Search for a game first before adding a new issue; if you find an existing issue that is out of date, reply to it.
- DO NOT create duplicate issues or common issues (i.e. Crashes in various games, Naughty Dog games are not booting etc).
- If some game boots on earlier versions and does not boot (or some bugs have appeared) on newer - report last working version.
- When game crashes - submit function name where it happened, like `nop nid:libkernel:A8249FA8320B967B:sceKernelMemoryPoolExpand`
- When you update or add additional information in an issue, please reply to the issue indicating your changes.
- Point a game's version - some games behaviors differently after updates. So you can try to update your game with patches, just mention it if somethings changes.
- *Optionally*: submit `dump_sym.exe -i ebootname.bin -o sometextfile.txt` output here using details tag (it looks like spoiler), or use webservices like pastebin. You can compile dump_sym.exe by yourself.
What files **ALLOWED** to submit - screenshots, log files (only if game crashes without errors and DO NOT whole log as is, just updload it as txt-file).
What files are **RESTRICTED AND BANNED** - **ANY** copyrighted content like eboot.bin, sprx or prx files, SDK leaked files, PKG files and homebrew applications made with official SDKs.

**Status labels**:

-   `status-playable`  - Boots and plays without any crashes or GPU bugs of any kind, and at a speed fast enough to reasonably enjoy on an average PC.
-   `status-ingame`  - Boots and goes in-game but suffers from one or more of the following: crashes, deadlocks, GPU bugs, bad audio, or is simply too slow. Game still might able to be played all the way through, but not as the game is intended to play.
-   `status-menus`  - Boots and goes past the title screen but does not make it into main gameplay.
-   `status-boots`  - Boots but does not make it past the title screen.
-   `status-nothing`  - Does not boot/shows no signs of life.
-   `issues-video`- There are graphics corruptions, missing textures, exploded polygons, no output etc.
-   `issues-audio`  There are sound corruptions, missing sounds, cracks etc.

