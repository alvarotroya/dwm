# My dwm build

This is my current dwm build (it is always a WIP).

For a list of the applied patches see [patches.md](./patches/patches.md).

## Dependencies

`libxft-dev libxinerama-dev`

## Starting DWM

Contents of `.xinitrc`
``` bash
#!/bin/sh

# source .xprofile if existent
[ -f ~/.xprofile ] && . ~/.xprofile

# start dwm
exec dwm
```

Contents of `.xprofile`
``` bash
wmname LG3D
customkeymaps
```
