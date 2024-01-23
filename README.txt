Madotsuki Spritesheet Organization Style:

	Each sprite needs to be 24x32 pixels. If each effect can be separated into 
it's own sheet, that would be awesome. 

Each spritesheet should be organized likeso:

	each walk cycle should have 3 frames just like the original game, with the 
original 4 organized in the first 4 columns in the top 3 rows, in these directions:
south, north, east, west. 

	The new walkcycles should be organized in the first 4 columns in rows 4-6 likeso: 
southWest, northWest, northEast, southEast.

	any extra animations in the effect should be in columns 5+. each animation can be 
given its own column, if it has more than 6 frames it can go into the next column as well.

for example, say we have animation A with 5 frames, and animation B with 7 frames
      C1 C2 C3
row 1 A1 B1 B7
row 2 A2 B2
row 3 A3 B3
row 4 A4 B4
row 5 A5 B5
row 6    B6

	anything that should show up as transparent needs to have complete alpha 
transparency. I know this seems redundant to say, but a huge portion of the 
sprites in the original game do not use alpha to denote transparency. 

	To give the new sprites, I'll setup a github repo, just DM me a link to your 
github account on discord and I'll send you an invite to the github repo so you can 
commit to your own branch. My discord is nailbataubrey. Just explain that you're DMing
me about spritesheets so I know you're not a scammer xD

	I want to thank anyone making sprites for this project so much! If you don't 
want to worry about organizing the spritesheets, just upload your work in the related 
effect's file folder, and I can do it later myself. Just make sure you label each 
animation within the spritesheet itself.