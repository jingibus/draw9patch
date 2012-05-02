draw9patch 
==========

A patched version of draw9patch that is much more pleasant to use, especially
on a mac.

Why I Dislike draw9patch 
------------------------

draw9patch is my least favorite part of the android SDK for three reasons:

1. It does not use a native mac file open/close dialog. It uses an alternative
abomination, apparently preferred by Swing.
2. If you edit a png in draw9patch and then try to save it, it will not attempt
to save it in the same directory as the png you were editing (which is what
you want, 99% of the time). It will open the (awful) save dialog in your
home directory.
3. When you are editing your 9patch, you have to draw exactly on the magic
pixel boundary. Filling in this magic pixel line for an image with
dimensions in the hundreds of pixels can lead to self harm.

Apart from these easy to fix flaws, it is a fine tool. With these flaws, it is
a signifant irritation in my workflow.

What This draw9patch Does Differently
-------------------------------------

1. It uses the native mac file open/close dialog.
2. When you open a png for 9patch editing and save it, it starts out in 
the same directory as that png.
3. If you're anywhere close to one of the borders of the image, drawing
applies to that border. It's slightly tricky close to the edges, but eh. 
No big deal.

Any Further Development Planned?
--------------------------------

It is said that the truly wise never do anything at all. Having accomplished
this foolishness, I hope to fill this project with wisdom.
