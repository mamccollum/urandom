# CTRL+V
`CTRL+V` is a useful key in the shell. 

Example of how it can be used:

If my backspace key is messed up on my terminal (ex. it can't auto-detect it from the termcap), I can fix this by typing:
```
stty erase <CTRL+V><BACKSPACE>
```
And this will essentially type the backspace key, but without executing it's function. (In this case, `^H` or `^?` will usually appear)
