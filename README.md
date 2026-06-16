### Hyprland bind viewer
1. Clone repo
2. install `aylurs-gtk-shell` from AUR
3. Run: `ags run <your-path-here>/app/app.js`

#### Description

The App reads exising keybinds via `hyprctl binds -j` and make a virtual keyboard with highlighted assigned keys with description in tooltips. 
Required to have desciuption field in your binding config: 
```
hl.bind(MainMod .. " + Return",     hl.dsp.exec_cmd(DefaultTerminal), { description = "kitty terminal"})
``` 
Shows only 1st lvl binds (no other mod keys) with mainMod = SUPER. Easy way to check what keys are unassign.
