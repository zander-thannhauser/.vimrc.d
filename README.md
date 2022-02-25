
# .vimrc.d

This is yet another repo for somebody's `.vimrc` files. This one is mine.

In attempt to be organized, the actual content of the `.vimrc` is just:

```

for file in globpath("$HOME/.vimrc.d", "**/*.vim", 0, 1)
	execute "source " . file
endfor

```

This enables the true content of `.vimrc` to be organized into specific files
for specific purposes. I'll also put plugins in here, so my entire vim
environment can be consistent across machines.
