## UNPATCH IPC FIRST
The last patch applied is dwm-ipc, which is highly recommended to be applied last for compatability with any other patches.

To unpatch it, run `patch -p1 -R patches/dwm-ipc-20201106-f04cac6.diff`

### If it fails,

You may face a hunk failing and outputting a "file.ext.rej"

All you need to do is open the patched and .rej files and manually see the diff file

Most of the time the error is due to lines being in different places, so search for the lines
being removed and you should see them
