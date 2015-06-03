Libash
======

Collection of scripts that will make your bash experience much more pleasant.



Installation
------------

Simply clone this repo, and add this to your `.bashrc`

```
export LIBASHDIR="/your/path/here"
source "$LIBASHDIR/libash"
```



Stuff included (now with screenshots!)
--------------------------------------
(click on the pictures to enlarge them)

feature                                                       | example
--------------------------------------------------------------|------------------------------------------------------
correction system                                             | ![correction system](http://i.imgur.com/798lKDc.png)
configurable short cwd in prompt                              | ![short cwd](http://i.imgur.com/eXYhJXb.png)
**greatest** vim completion **ever** (easy to adapt to other editors) that never completes binary files and completes tags when you use vim -t<tab> | ![vim completion](http://i.imgur.com/JRo8jaw.gif)
increment and decrement number with `C-x` and `C-a`           | ![c-xc-a](http://i.imgur.com/IQdLXUd.gif)
hook system to bind actions to certain events                 | changed directory, enter a new git repo...
something similar to `moreutils` that works with shell syntax | <code>mispipe 1  cmd1 &#124; grep string &#124; cmd2</code> returns the exit code of grep
useful functions and much moar                                | ![isup](http://i.imgur.com/k5ztoJj.png)
![fuzzyfind](http://i.imgur.com/4gEbAUa.png)                  | ![mkdirc uprm](http://i.imgur.com/XXhY3lW.png)



License
-------

Released under the ISC license. It's freeeeeeeeeeeeeeeeee!

