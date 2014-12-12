Libash
======

Collection of scripts that will make your bash experience much more pleasant.



Usage
-----

Simply clone this repo, and source `libash` in your `.bashrc`.



Stuff included
--------------

- colorful progressbar
- b/w progressbar
- right prompt (to come)
- chpwd hook
- something similar to `moreutils`, but that works with builtins and shell functions



Usage
-----

`sed "s/root/toor/" /etc/passwd | grep -v joey | sponge /etc/passwd`

*sponge* will soak up standard input and write to a file

`chronic command file`

*chronic* will run a command quietly unless it fails 
(applies to builtins and shell functions as well)

`mispipe [num] command0 args | command1 args | command2 args | command3`

*mispipe* will run the pipeline, and will return the exit code of the n-th command
(applies to builtins and shell functions as well)  
If `[num]` is not provided, returns the exit code of command0  
If `[num]` is bigger than the number of commands+1, it returns the exit code of the last one



License
-------

Released under the ISC license. It's freeeeeeeeeeeeeeeeee!

