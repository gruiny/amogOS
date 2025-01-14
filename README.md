# AmogOS
Among Us-inspired OS ඞ.

![amogOS screenshot with anne wallpaper](https://user-images.githubusercontent.com/44128563/124066315-b01f7a80-d9f5-11eb-9c2a-968f459a6e7c.png)

This was mostly inspired by https://www.reddit.com/r/unixporn/comments/nhomed/cinnamon_amogos_is_complete_icon_art_idea_by_u/ (and also yoinks the icon and wallpaper from it, originally made by `u/_peekatchoo_` on Reddit).

EDIT: AHHH Mutahar covered the OS!!!!! I am beyond words that he made a video on this sussy OS. This OS was inspiried by other similiar mods people have made (credit above). I'm just gonna sneak in my youtube channel here to capitalize on the fame :) I cover Raspberry Pi-related content:  
pi news : https://www.youtube.com/channel/UCmp6JswV90SV5agNFGQuWkw
also link to moon, the head dev of the project
moon1789 : https://www.youtube.com/channel/UC9izewtsA__dtENOC_nNkBA 

## Download:  
(This build is for RPI 3 and 4, x86 build coming soon)
https://github.com/jostroOS/amogOS/releases/latest

## Important Notice for QEMU Users:
This is meant for RPI 3 and 4. If you would like to run it on a x86 system, you can do so via QEMU. Download it [here](https://drive.google.com/file/d/1wgkJYwNV7jqxNFW_uRPPZ3JKvd87mVPE/view?usp=sharing) and read the instructions inside the zip to find how to replace the Twister OS image with amogOS. If the latest version of Amogos dosent work on QEMU, try an older release (we dont know whats the issue but thats the only solution for now) , Mostly v1.2.0 or v1.0.0 should do the Job!

### Get support on Discord:
https://discord.gg/k4d24VaAJN

## Features
- Kinda sussy
- Custom wallpapers and start menu icon
- Grey color palette to match Among Us
- Custom neofetch logo
- [MCPI Reborn](https://gitea.thebrokenrail.com/TheBrokenRail/minecraft-pi-reborn) (It's recommended you use the included `gMCPIL` launcher to launch the game)
- Uses Openbox WM, allowing you to switch to 4 desktop spaces with the scroll wheel, similar to macOS.

### RPI only features, not present on x86 build
- [among-sus](https://git.sr.ht/~martijnbraam/among-sus), an open-source among us alternative playable in terminal (use `among-sus-server` to host a localhost server and `among-sus` to connect to a server hosted on the current device, or `nc <ip on your LAN network>` to join a game on your network)
- 64-bit kernel enabled by default for speed, as well as to enable Wine support on RPI 3
- Preinstall CommanderPi, piwiz, Box86, tldr, Pi Power Tools, pi-apps, Colour Emoji Font, Stacer, legendary launcher (to replace Epic Games Launcher), and preinstall a 64-bit container to run aarch64 apps
- Wine + box86 preinstalled for x86 windows syscall translation
- piKiss and pi-apps preinstalled so you can install some games and also A M O N G U S
(Among Us will run at ~5 fps on multiplayer play. It's a really crap framerate, but for a game never intended to run on a CPU the size of a thumb with 2 layers of syscall translation (x86 windows -> x86 linux -> arm linux), it's decent. A small resolution is needed for the game to run without insane lag.)
- You can overclock your RPI with Commander Pi to get slightly more performace.

## Notes
- (RPI version only) You can use [vdesktop](https://github.com/Botspot/vdesktop) to test out the OS in a container without any lag and flashing needed on an ARM host.
- (RPI version only) Default username is "pi" and password is "raspberry"
- (x86 version only) Default username is "amogos" and password is "amogos"
- **AmogOS is not a custom OS, it's just riced RPi OS/Debian Buster. It doesn't have any custom written source code.**

# Credits
- Main dev and founder: Moon1789#6969 (https://www.youtube.com/channel/UC9izewtsA__dtENOC_nNkBA)
- Co-dev/OS packager: RPiNews#0816 (https://www.youtube.com/channel/UCmp6JswV90SV5agNFGQuWkw) (I also go by https://www.youtube.com/channel/UCOImY0CpIrsOmbODaWYt17A for those of you who see me comment on amogOS related content and call me sussy imposter :p)
- Thanks to peek#0101 (Again) for making the wallpapers.
- Thanks to the jostroOS dev team for letting us use their GH org and website to host downloads!
