# This DWX build
- Uses DWM Verson 6.2
- Replaced Tag Numbers with icons from @BreadOnPenguins build
- And also statusbar Icon also replaced with Hack Nerd Mono Glyphs
- Has not seperated common DWM shortcuts and users custom shortcuts for daily use
- Has successfully implemented working multiple scratch pads.

![imgmyartixrice](http://0x0.st/-KvC.png)

## Some Honorable Mentioned Keybinds
Although there are more check out `config.h` file

| Usecase             | Keys                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Terminal | Super + Enter |
| lf filemanager | Super + Semicolon |
| Scratchpad Terminal | Super + Shift + Semicolon |
| Dmenu | Super + d |
| Vol Up | Super + plus |
| Vol Down | Super + minus |
| Mute | Super + Shift + m |
| Log out Menu | Super + backspace |
| Fibonacci Layout | Super + y |
| Stacking Layout | Super + t |
| Dwindle Layout | Super + u |
| Monocol Layout | Super + i |



## Patches and features

- Clickable statusbar with luke's build of [dwmblocks](https://github.com/lukesmithxyz/dwmblocks).
- Reads xresources colors/variables (i.e. works with `pywal`, etc.).
- scratchpad: Accessible with mod+shift+enter
- New layouts: fibonacci, bstack, deck, centered master and more. All bound to keys `super+(shift+)t/y/u/i`.
- True fullscreen (`super+f`) and prevents focus shifting.
- Windows can be made sticky (`super+s`).
- stacker: Move windows up the stack manually (`super-K/J`).
- shiftview: Cycle through tags (`super+g/;`).
- vanitygaps: Gaps allowed across all layouts.
- swallow patch: if a program run from a terminal would make it inoperable, it temporarily takes its place to save space.
- **work well with pywal**

## Please install `libxft-bgra`!
[not sure in 2025 this issues must have fixed I hope so.]

This build of dwm does not block color emoji in the status/info bar, so you must install [libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) from the AUR, which fixes a libxft color emoji rendering problem, otherwise dwm will crash upon trying to render one. Hopefully this fix will be in all libxft soon enough.
