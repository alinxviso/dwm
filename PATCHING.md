## How to patch

There are 2 main ways to patch using a diff file, using patch(1) or `git apply <patch>`

### patch(1)

To patch and unpatch using patch(1), you can either pipe or redirect the patch like so:

To patch
```
patch -p1 < patches/dwm-patch.diff
curl https://dwm.suckless.org/patches/patch/dwm-patch.diff | patch -p1
```

To unpatch
```
patch -R -p1 < patches/dwm-patch.diff
curl https://dwm.suckless.org/patches/patch/dwm-patch.diff | patch -R -p1
```

### git

To patch
```
git apply patch/dwm-patch.diff
```
