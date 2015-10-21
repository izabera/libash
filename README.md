Libash
======

Collection of scripts that will make your bash experience much more pleasant.



Installation
------------

Simply clone this repo, cd in your new directory and run `./install`

```bash
git clone https://github.com/izabera/libash.git && cd libash && ./install
```



Stuff included (now with screenshots!)
--------------------------------------

- **>>> CORRECTION SYSTEM <<<**  
   ![correction system](http://i.imgur.com/798lKDc.png)
- configurable short cwd in prompt  
   ![short cwd](http://i.imgur.com/eXYhJXb.png)
- **greatest** vim completion **ever** (easy to adapt to other editors) that never completes binary files and completes tags when you use `vim -t<tab>`:  
   ![vim completion](http://i.imgur.com/JRo8jaw.gif)
   note: it _never_ completes binary files, without relying on the extension
- increment and decrement number with `C-x` and `C-a`  
   ![c-xc-a](http://i.imgur.com/IQdLXUd.gif)
- hook system to bind actions to certain events:  
   changed directory, enter a new git repo...
- something similar to `moreutils` that works with shell syntax:  
   `mispipe 1  cmd1 | grep string | cmd2` returns the exit code of grep
- useful functions and much moar  
  - connectivity testing
   ![isup](http://i.imgur.com/k5ztoJj.png)  
  - fuzzy find
   ![fuzzyfind](http://i.imgur.com/4gEbAUa.png)  
  - quicker navigation
   ![mkdirc uprm](http://i.imgur.com/XXhY3lW.png)



License
-------

Released under the ISC license. It's freeeeeeeeeeeeeeeeee!

