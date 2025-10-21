# dwm

these are my dwm configs, if you want to see them, switch branches to the version you want

old readme can be found at README

so far my main is 6.2, and will probably have the most patches

default branch is 6.2

current branch is 6.2

# BSD USERS

#### THIS WILL NOT COMPILE ON ANY BSD
One of the patches depends on the epoll syscall, which is only available on linux, making it impossible to compile on anything else.
I am currently testing to see which patch it is, but it is most likely the dwm-ipc patch

## patches

all patches applied, in order, can be found in the patches/applied.txt file

all patches will use the base -6.2.diff version if available

patches that aren't added for special reasons but still function can found in patches/special

patches that are neat but i don't really want are in patches/optional

## dependencies

the winicon patch needs imlib2, which is usually packaged on most distros
dwm-ipc requires yajl, also packaged on most distros

### other
look [here](https://github.com/mihirlad55/dwm-ipc/wiki/) for how to use the dwm-ipc, which is very useful for external bars
