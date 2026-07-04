##System
- Os: Ubuntu 26.04
-  Laptop: Acer Swift SF114-33

##Installed / Tools
- Git
- Vs Code
- Python 3
- Google Chrome
- Obsidian (AppImage)
- Nmap
- Wireshark
- Burp Suite (planned)

##Changes made today
- Fixed broken XDG user directories
- Swiched Obsidian from Snap -> AppImage
- Fixed AppImage FUSE issue (libfuse2 install)
- Fixed sandbox launch issue (--no-sandbox workaround)

##Issues encountered
- Obsidian Snap did not launch (silent failure)
- AppImage required FUSE and sandbox workaround
- Missing Documents/Downloads due to broken XDG config

##Fixes applied
- `xdg-user-dirs-update --force`
- installed libfuse2
- used --no-sandbox for Obsidian

##Notes / Learnings 
- Linux apps behave differently on install method
- Snap apps are sandboxed and can silently fail
- AppImage is more portable but may need dependencies

##Next steps
- Learn Linux, understanding deeper mechanics
- Get experience in documentations, throug obsidian and github
- Set up Vs code
- Organize application folder