MirrorSelected.py tutorial
by Austin Fitzpatrick

last updated:
March 19th, 2018

Description:
This script can be used to create a mirrored object across chosen axis. 
This can be set up to display a real time demo of the object’s composition in a large mirror(build as a window) without having to ray-trace it.

How to use:

-import the code to define the function.

-Have an object available for selection or create one.

-Select the object you wish to mirror.

-Type MirrorSelected( into a python script to execute.

-Type the axis(xyz) you wish for the object to mirrored across.
 This can be one or many axis (default is x) and in any order.
 you can type your axis as a single string i.e. (“xz”)
 or just use the letter i.e. (x)
 to do more than one axis, add each letter i.e. (z+x+y)

-close your parentheses

-Execute.

Your object should duplicate and the new object’s movements will automatically and continually move to mirror the movements of the original object.