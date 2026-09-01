Suckless programs for debian

Dependencies: git build-essential libx11-dev libxft-dev libxinerama-dev

to get fixed font working (mint):
Deleted /etc/fonts/conf.d/70-no-bitmaps-except-emoji.conf

Refreshed the font cache with fc-cache -f

Configured st with "Misc Fixed:style=SemiCondensed:fullname=Misc Fixed SemiCondensed:pixelsize=18"
