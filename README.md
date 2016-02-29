# minecraft

Fun little project in minecraft to convert a png into a TPPI2 minecraft mural.  Didn't work out because of some amazing amounts of inconsistencies between mods and texture standards.

How it works:
1. Recursively unzip TPPI2 jars and copy textures and texture metadata to local directory.
2. Ignore those Os and pull every pixel's color/alpha data of every TPPI2 texture.
3. Build a minecraft OpenComputers 3d printer. Took about 2 weeks to get to this point.
4. Run this script against a png file. It'll create a bunch of voxel shape files.
5. With the minecraft computer's git client, pull the .3dm files and print them one at a time.
6. Cry once they look like garbage because of inconsistent block textures (depth, transparency, template on top of template, etc). 
7. Spend a few hours with jad and search for any semblance of a consistent pattern.
8. Go to sleep and never look back. 
