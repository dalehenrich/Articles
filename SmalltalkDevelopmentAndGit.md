In January of 1985 I started working in Tektronix Smalltalk. 
At that time you used changesets to manage code.
Believe it or not, when a team worked with Smalltalk in those days, the image was passed around from developer to developer and each of the developers integrated their changes into the “master image”. 
I had been working in FORTRAN for 4 years or so and (silly me) I wanted to be able to build my image from scratch without having to manually integrate changesets.
I wrote a tool that saved changesets to disk (early form of package) and used RCS (predecessor to CVS) to version the code. 
I used a predecessor to the [Change Sorter][1] tool to sort changes for a unit of work into the "packages" before saving it.
[Ward Cunningham][2] created the Change Sorter after I gave him a demo of the tool that I was using :)

[1]: http://wiki.squeak.org/squeak/2145
[2]: https://en.wikipedia.org/wiki/Ward_Cunningham
