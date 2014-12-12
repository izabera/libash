Libash
======

Collection of scripts that will make your bash experience much more pleasant.



Installation
------------

Simply clone this repo, and add this to your `.bashrc`.

```
export LIBASHDIR="/your/path/here"
source "$LIBASHDIR/libash"
```



Stuff included
--------------

- progressbars
- right prompt (to come)
- chpwd hook
- something similar to `moreutils`, but that works with shell stuff



Usage
-----

`sed "s/root/toor/" /etc/passwd | grep -v joey | sponge /etc/passwd`

*sponge* will soak up standard input and write to a file

`chronic command file`

*chronic* will run a command quietly unless it fails  
Non interactively, it applies to regular commands, builtins and shell functions  
Interactively it applies to compound commands as well

`mispipe [num] command0 args | command1 args | command2 args | command3`

*mispipe* will run the pipeline, and will return the exit code of the n-th command
Only usable interactively, it applies to regular commands, builtins, shell
functions and compound commands as well  
If `[num]` is not provided, returns the exit code of command0  
If `[num]` is bigger than the number of commands+1, it returns the exit code of the last one

`command | ts [format]`

*ts* will timestamp the data stream  
If no format is provided, +%c will be used

`backup [file...]`

*backup* will copy the files in /backup, with a unique (timestamped) filename

`isempty [dir]`

*isempty* returns 0 if the directory is empty, 1 otherwise




License
-------

Released under the ISC license. It's freeeeeeeeeeeeeeeeee!

