# Vim Navigation

Up-Down Left-Right
``` bash 
h  # left
j  # down
k  # up
l  # right
```

page down and up
``` bash
ctrl-f # page down (forward)
ctrl-b # page up (back)
```

forward and backword by word
``` bash 
w   # move forward by word
W   # move forward by word with whitespace as word boundries

b   # move backword by word
B   # move backword by word with whitespace as word boundries
```

begining - end of file
``` bash
gg or 1gg  # move to the begining of file
G  or $G  # move to the end of file
```

Go to line:
1. Mode normal <br/>
    Go to line number:

    ``` bash
    <LINE_NUMBER>gg or <LINE_NUMBER>G   # example 27gg or 27G
    ```
2. Mode line <br/>
    Go to line number:
    ``` bash
    :<LINE_NUMBER><ENTER>  # example :27<ENTER>
    ```
    Go to last line:
    ``` bash
    :$<ENTER> # example :$<ENTER>
    ```

## Ruler
``` bash
:set ruler!<ENTER> #enable ruler

# then
ctrl-g #show the ruler of current cursor position

:set noruler! #disable ruler
```