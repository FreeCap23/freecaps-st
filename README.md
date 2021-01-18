# FreeCap's Build of st

About
==========================
This build of st is pretty lightly customized. Nothing crazy. I guess I only uploaded it to GitHub if I ever reinstall Linux and need a quick setup, so if you want to use this thing and it's not supported anymore, don't ask. Why would you want to use this though?

Patches
==================================================
- anysize (st-anysize-20201003-407a3d0.diff)
- clipboard (st-clipboard-0.8.3.diff)
- ligatures (st-ligatures-scrollback-20200430-0.8.3.diff)
- scrollback (st-scrollback-0.8.4.diff)
- rightclickpaste (st-rightclickpaste-0.8.2.diff)
- w3m (st-w3m-0.8.3.diff)

Dependencies
=============================================================
- CaskaydiaCove Nerd Font Mono  =>  For the terminal font and the symbols in dwm-bar & the trash can tag.
- PyWal  =>  For the color scheme. Pretty sure you need to run it at least once for it to work.
- Harfbuzz  =>  For the ligatures

Installation
=============================================================
1) Git clone this repo somewhere, and compile by running `sudo make clean install`.

Configuration
============================================================
Edit config.h and recompile.
