# Challenge Name
epic filesystem quest

## My solve
**Flag:** `pwn.college{c-UOLPuTUv0Zg6O8Vg7OjOFkLJe.QX5IDO0wyNzEzNzEzW}'

```bash
Connected!
hacker@commands~an-epic-filesystem-quest:~$ cd /
hacker@commands~an-epic-filesystem-quest:/$ ls
WHISPER  boot       dev  flag  lib    lib64   media  nix  proc  run   srv  tmp  var
bin      challenge  etc  home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~an-epic-filesystem-quest:/$ cat WHISPER
Yahaha, you found me!
The next clue is in: /opt/splitmind/.git/refs/heads

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/$ ls /opt/splitmind/.git/refs/heads
README-TRAPPED  master
hacker@commands~an-epic-filesystem-quest:/$ cat master
cat: master: No such file or directory
hacker@commands~an-epic-filesystem-quest:/$ cat /opt/splitmind/.git/refs/heads/master
a95b50f308f6e78b15c1fae9ed11239a6b70bdb7
hacker@commands~an-epic-filesystem-quest:/$ cat /opt/splitmind/.git/refs/heads/README-TRAPPED
Congratulations, you found the clue!
The next clue is in: /usr/share/icons/Adwaita/512x512/mimetypes

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/icons/Adwaita/512x512/mimetypes
application-x-executable.png  text-x-preview.png  x-office-presentation.png
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/icons/Adwaita/512x512/mimetypes -a
.  ..  .SECRET  application-x-executable.png  text-x-preview.png  x-office-presentation.png
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/icons/Adwaita/512x512/mimetypes/.SECRET
Great sleuthing!
The next clue is in: /opt/linux/linux-5.4/drivers/hid
hacker@commands~an-epic-filesystem-quest:/$ ls /opt/linux/linux-5.4/drivers/hid -a
.                      hid-asus.c             hid-ids.h                hid-picolcd_cir.c      hid-sjoy.c
..                     hid-aureal.c           hid-input.c              hid-picolcd_core.c     hid-sony.c
.built-in.a.cmd        hid-axff.c             hid-input.o              hid-picolcd_debugfs.c  hid-sony.o
.hid-a4tech.o.cmd      hid-belkin.c           hid-ite.c                hid-picolcd_fb.c       hid-speedlink.c
.hid-apple.o.cmd       hid-belkin.o           hid-ite.o                hid-picolcd_lcd.c      hid-steam.c
.hid-belkin.o.cmd      hid-betopff.c          hid-jabra.c              hid-picolcd_leds.c     hid-steelseries.c
.hid-cherry.o.cmd      hid-bigbenff.c         hid-kensington.c         hid-pl.c               hid-sunplus.c
.hid-chicony.o.cmd     hid-cherry.c           hid-kensington.o         hid-pl.o               hid-sunplus.o
.hid-core.o.cmd        hid-cherry.o           hid-keytouch.c           hid-plantronics.c      hid-tivo.c
.hid-cypress.o.cmd     hid-chicony.c          hid-kye.c                hid-primax.c           hid-tmff.c
.hid-debug.o.cmd       hid-chicony.o          hid-lcpower.c            hid-prodikeys.c        hid-topseed.c
.hid-ezkey.o.cmd       hid-cmedia.c           hid-led.c                hid-quirks.c           hid-topseed.o
.hid-generic.o.cmd     hid-core.c             hid-lenovo.c             hid-quirks.o           hid-twinhan.c
.hid-gyration.o.cmd    hid-core.o             hid-lg.c                 hid-redragon.c         hid-u2fzero.c
.hid-input.o.cmd       hid-corsair.c          hid-lg.h                 hid-redragon.o         hid-uclogic-core.c
.hid-ite.o.cmd         hid-cougar.c           hid-lg.o                 hid-retrode.c          hid-uclogic-params.c
.hid-kensington.o.cmd  hid-cp2112.c           hid-lg2ff.c              hid-rmi.c              hid-uclogic-params.h
.hid-lg.o.cmd          hid-creative-sb0540.c  hid-lg3ff.c              hid-roccat-arvo.c      hid-uclogic-rdesc.c
.hid-lg4ff.o.cmd       hid-cypress.c          hid-lg4ff.c              hid-roccat-arvo.h      hid-uclogic-rdesc.h
.hid-lgff.o.cmd        hid-cypress.o          hid-lg4ff.h              hid-roccat-common.c    hid-udraw-ps3.c
.hid-microsoft.o.cmd   hid-debug.c            hid-lg4ff.o              hid-roccat-common.h    hid-viewsonic.c
.hid-monterey.o.cmd    hid-debug.o            hid-lgff.c               hid-roccat-isku.c      hid-waltop.c
.hid-ntrig.o.cmd       hid-dr.c               hid-lgff.o               hid-roccat-isku.h      hid-wiimote-core.c
.hid-petalynx.o.cmd    hid-elan.c             hid-logitech-dj.c        hid-roccat-kone.c      hid-wiimote-debug.c
.hid-pl.o.cmd          hid-elecom.c           hid-logitech-hidpp.c     hid-roccat-kone.h      hid-wiimote-modules.c
.hid-quirks.o.cmd      hid-elo.c              hid-macally.c            hid-roccat-koneplus.c  hid-wiimote.h
.hid-redragon.o.cmd    hid-emsff.c            hid-magicmouse.c         hid-roccat-koneplus.h  hid-xinmo.c
.hid-samsung.o.cmd     hid-ezkey.c            hid-maltron.c            hid-roccat-konepure.c  hid-zpff.c
.hid-sony.o.cmd        hid-ezkey.o            hid-mf.c                 hid-roccat-kovaplus.c  hid-zydacron.c
.hid-sunplus.o.cmd     hid-gaff.c             hid-microsoft.c          hid-roccat-kovaplus.h  hidraw.c
.hid-topseed.o.cmd     hid-gembird.c          hid-microsoft.o          hid-roccat-lua.c       hidraw.o
.hidraw.o.cmd          hid-generic.c          hid-monterey.c           hid-roccat-lua.h       i2c-hid
Kconfig                hid-generic.o          hid-monterey.o           hid-roccat-pyra.c      intel-ish-hid
Makefile               hid-gfrm.c             hid-multitouch.c         hid-roccat-pyra.h      uhid.c
TRACE                  hid-google-hammer.c    hid-nti.c                hid-roccat-ryos.c      usbhid
built-in.a             hid-gt683r.c           hid-ntrig.c              hid-roccat-savu.c      wacom.h
hid-a4tech.c           hid-gyration.c         hid-ntrig.o              hid-roccat-savu.h      wacom_sys.c
hid-a4tech.o           hid-gyration.o         hid-ortek.c              hid-roccat.c           wacom_wac.c
hid-accutouch.c        hid-holtek-kbd.c       hid-penmount.c           hid-saitek.c           wacom_wac.h
hid-alps.c             hid-holtek-mouse.c     hid-petalynx.c           hid-samsung.c
hid-apple.c            hid-holtekff.c         hid-petalynx.o           hid-samsung.o
hid-apple.o            hid-hyperv.c           hid-picolcd.h            hid-sensor-custom.c
hid-appleir.c          hid-icade.c            hid-picolcd_backlight.c  hid-sensor-hub.c
hacker@commands~an-epic-filesystem-quest:/$ cat /opt/linux/linux-5.4/drivers/hid/TRACE
Great sleuthing!
The next clue is in: /opt/busybox/busybox-1.33.2/modutils

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/$ ls /opt/busybox/busybox-1.33.2/modutils -a
.                .modinfo.o.cmd         Config.src    built-in.o         lib.a      modprobe-small.c  modutils.c
..               .modprobe-small.o.cmd  INFO-TRAPPED  depmod.c           lsmod.c    modprobe-small.o  modutils.h
.built-in.o.cmd  .modutils.o.cmd        Kbuild        depmod_process.sh  modinfo.c  modprobe.c        modutils.o
.lib.a.cmd       Config.in              Kbuild.src    insmod.c           modinfo.o  modutils-24.c     rmmod.c
hacker@commands~an-epic-filesystem-quest:/$ cat /opt/busybox/busybox-1.33.2/modutils/INFO-TRAPPED
Yahaha, you found me!
The next clue is in: /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Latin-Modern/Symbols
hacker@commands~an-epic-filesystem-quest:/$ ls  /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Latin-Modern/Symbols -a
.  ..  GIST  Regular
hacker@commands~an-epic-filesystem-quest:/$ cat  /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Latin-Modern/Symbols/GIST
Yahaha, you found me!
The next clue is in: /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Termes/Size4
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Termes/Size4 -a
.  ..  Regular  SNIPPET
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/javascript/mathjax/jax/output/HTML-CSS/fonts/Gyre-Termes/Size4/SNIPPET
Yahaha, you found me!
The next clue is in: /usr/share/doc/python3-urllib3

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/doc/python3-urllib3 -a
.  ..  .MESSAGE  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/doc/python3-urllib3/MESSAGE
cat: /usr/share/doc/python3-urllib3/MESSAGE: No such file or directory
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/doc/python3-urllib3./MESSAGE
cat: /usr/share/doc/python3-urllib3./MESSAGE: No such file or directory
hacker@commands~an-epic-filesystem-quest:/$ cat /usr/share/doc/python3-urllib3/.MESSAGE
Yahaha, you found me!
The next clue is in: /usr/share/locale/zh_Hant

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/$ ls /usr/share/locale/zh_Hant -a
.  ..  INSIGHT  LC_MESSAGES
hacker@commands~an-epic-filesystem-quest:/$ cd INSIGHT
bash: cd: INSIGHT: No such file or directory
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/locale/zh_Hant/INSIGHT
bash: cd: /usr/share/locale/zh_Hant/INSIGHT: Not a directory
hacker@commands~an-epic-filesystem-quest:/$ cd /usr/share/locale/zh_Hant/
hacker@commands~an-epic-filesystem-quest:/usr/share/locale/zh_Hant$ cat INSIGHT
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{c-UOLPuTUv0Zg6O8Vg7OjOFkLJe.QX5IDO0wyNzEzNzEzW}
```

## Incorrect tangents I went on
silly error - trying to cd into a file rather than the directory


## What I learned
to LIST all files first and then CAT them.
to always check for hidden files (. preceding).
to list and cat files without entering said directory.

## References 
none
