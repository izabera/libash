Simple Bash Progressbar
=======================

Just a simple progress bar for your scripts.


Usage
-----

This is a sample script that downloads some pictures from a website:

```
printbar "0" "$max"
for (( i=0; i<max; i++ )) ; do
  wget -q "$url/$i.png"
  printbar $((i+1)) "$max"
done
```

Ok there's little point in this since `wget` already provides progress bars,
but we can use it for moving files, printing stuff, showing progress on any
kind of script.


License
-------

This software is provided as is, with no warranty.
You're free to use, share, edit, eat, drink it however you want.

