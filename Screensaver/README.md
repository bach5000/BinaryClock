
# BinaryClock ScreenSaver

## by David Enderson

### How to read the Binary Clock:

Each column stands for a digit in a 24 hour clock with the format: xx:xx:xx
each column is configured like this
```
8
4
2
1
```

so if you wanted 2 you would see  (O being off, X being on)
```
O
O
X
O
```
5 would be:
```
O
X
O
X
```
so 8:57:12pm would be 20:57:12 which would look like:
```
OO	OO	OO
OO	XX	OO
XO	OX	OX
OO	XX	XO
```

### Why I wrote this:

I was inspired to write this program when I saw my college roommate, Ben Kinder, running a program like this on his gnome bar in Linux.  I have no idea if this is the "official" layout of a binary clock or if there even is such a thing.


### How I wrote this:

When I made this I took the sample screen saver code that came with BeOS, gutted it, and added my BinaryClock code.  The graphics were made with the POVRay port for Be, and I compiled them into the saver by using PaintShopPro 6 to convert them to raw files, then used the craw command to make them into character arrays to be included in the program.  If you know of an easier way to add graphics to a program, please let me know.  I am having trouble with this method getting the 15x15 preview graphics to work.  That's why I used my old BinaryClock graphics.


### Can I really use this?

YES, you really can use this to tell time.  It just takes a little getting used to.


### Version Notes:

I have given this a version number of 0.7 because I plan to:
* allow the user to choose ANY color
* get the preview colors right

Revisions since version 0.3:
* graphics added
* streamlined
