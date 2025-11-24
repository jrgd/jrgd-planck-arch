# jrgd planck keymap

base layout altered to make room for:
- triangle-shape arrows
- esc-tab swap
- Fn key 'translation' from macOs -> create a specific layer (home, end, top and bottom shortcuts on arrows)
- the return of Print screen (was shift+sup+ 3/4 on macOs)
- function keys for Linux (essentially for now: f2 rename, f3 next-search)
- delete on layer 7 (fn)

todo:
- accents, special chars and diacritcs without compose


ref:
- https://docs.qmk.fm/reference_keymap_extras

QMK getting started on Arch
https://www.reddit.com/r/olkb/comments/7kircx/qmk_getting_started_on_arch/
(Posted the below over there)
- first time: install Package qmk (current is 1.1.8) then run `qmk setup`
- use the online configurator to customise your keymap; https://config.qmk.fm/#/planck/rev4/LAYOUT_ortho_4x12
- modify your layout; press compile then download firmware (you end up with a .hex file on your disk)
- reboot your keyboard in flash-mode (either turn off and restart pin-pressing the switch underneath; or reboot and press ESC - the keyboard wont be usable while in this mode)
- use that hex file you downloaded: `qmk flash planck_rev4_custom_keymap_name.hex`