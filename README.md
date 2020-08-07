# rancid
Here are some RANCID scripts for low-end switches, works with RANCID 3.7.

All copyrights are in files itself.

I'm not guaranteeing that this scripts will work with your equipment, but it MAY work, at least worked for me.

I've used as base various RANCID scripts(clogin, hlogin), but not yet contacted with developer for merging changes.

Scripts are:

csblogin - login script for Cisco Small Business switches (aka Cisco SF500, SF200). Yea, I know that RANCID supports this switches out-of-the-box, but for SF200 switch these scripts not works as intended, so I changed existing script.

hoclogin - HP Office Connect login script. I've used this script for HP Office Connect switches, like HP 1920-24 and HP 1920-48. They use CommWare5-like OS, but very limited and with common enable password (Jinhua1920unauthorized).

hocrancid - HP Office Connect RANCID script. Base for this script was hrancid, I've changed it a little for dealing with HP Office Connect switches.
