# rancid
DISCLAIMER: I'm no longer work with this switches due to job change. I have small knowledge of Perl, so mistakes may be present. I have no further plans to merge this into RANCID project, so you can do it by contacting developers of RANCID.

Here are some RANCID scripts for low-end switches, works with RANCID 3.7.
All copyrights are in files itself.
I'm not guaranteeing that this scripts will work with your equipment, but it MAY work, at least worked for me.

I've used as base various RANCID scripts(clogin, hlogin), but not contacted with developer for merging changes.

Scripts are:

csblogin - login script for Cisco Small Business switches (aka Cisco SF500, SF200). Yea, I know that RANCID supports this switches out-of-the-box, but for SF200 switch these script not works as intended, so I changed existing script.

hoclogin - HP Office Connect login script. I've used this script for HP Office Connect switches, like HP 1920-24. They use ComWare5-like OS, but limited and with common enable password (Jinhua1920unauthorized). Base for this script was h3clogin. Used with h3crancid.

hllogin - script for HP 1920S 48G (JL386A). They use some Linux as OS, so I've used hlogin script and made some changes to work with this switch.

hlrancid - RANCID script for HP 1920S 48G (JL386A). Base for this script is hrancid.
