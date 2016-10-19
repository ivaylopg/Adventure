###Colossal Cave Adventure

I compiled Adventure 2.5 [from source](http://rickadams.org/adventure/e_downloads.html), and it worked, but any time I tried to load a saved game it gave me a "Checksum error" and quit. That was a bummer.

Then I found the awesome 64-bit osx port of adventure by [Lobotomo](http://www.lobotomo.com/products/Adventure/), but it had a simulated terminal interface and I wanted to run it my _real_ terminal. (Or maybe I wanted to just be able to drop into playing a game while still looking like I was working...)

I pulled the compiled Adventure binary out of Lobotomo's app bundle and I am just using that directly. I'm pretty sure this is all kosher, given the original Adventure 2.5 license, but if anyone has a problem with this, let me know!

## Usage
You have to run `advent` from within it's directory or the program won't be able to load `adventure.text`.

I just set up an alias in my shell:
````bash
alias adventure="cd Path/To/Adventure && ./advent"
````

All saved games will be saved to this directory as well. Type `save` and then a filename to save, or `resume` and a filename to try to reload that file.

Happy hunting!

----

Don Wood's Adventure 2.5: (c) Copyright 1995 by Donald R. Woods.

This software may be freely redistributed if this notice is retained.
(The author apologises for the style of the code; it is a result of
running the original Fortran IV source through a home-brew Fortran-to-C
converter.)
