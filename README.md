# inline-mk47-keyboard-add-character-functionality
Adds missing keys to the mk47 wired mechanical rgb keyboard 

MUST: 
- have QMK installed and setup
- replace the file at /qmk_firmware/keyboards/inland/mk47/keymaps/default with this new keymap.c
- `qmk flash -kb inland/mk47 -km default`
- unplug and replug keyboard while holding ESC to launch bootloader
- enjoy the ability to write the following characters: -_=+[{]}\|`~'"
NOTE: this change will override the media keys because I do not need them. 
