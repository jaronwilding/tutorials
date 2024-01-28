# Houdini - Rotate Towards Direction

[![Houdini - Rotate Towards Direction Image](https://img.youtube.com/vi/m0G6wZh0BA8/0.jpg)](https://www.youtube.com/watch?v=m0G6wZh0BA8 "Houdini - Rotate Towards Direction")

### Taken from YouTube Description:

This setup contains VEX, VOPs and For-Loops, most of which I do explain. Some parts I gloss over, and if it's needed, further tutorials can be made on them. However the focus was on implementing a procedural rotation setup, which is what I hope I have managed to teach.

If anyone knows a better method \ implementation, feel free to mention them below!

Some links that were discussed on finding the rotation:
[CGSociety - Rotation Matrix from 2 Vectors](https://forums.cgsociety.org/t/rotation-matrix-from-2-vectors/1295254)
[Math Stack Exchange - Calculate Rotation Matrix to Align Vector A to Vector B in 3D](https://math.stackexchange.com/questions/180418/calculate-rotation-matrix-to-align-vector-a-to-vector-b-in-3d)

---

### Update 2024

Special thanks to user [Z NBK](https://www.youtube.com/channel/UCc1lGvVnAdk5rhSWpIU4Tsg) for pointing me towards (lol) the dihedral function.

The HIP file now contains two implementations, the first taken directly from the tutorial itself, with only one modification at the end, where I use the name attribute to scatter over points. The second implementation directly uses the dihedral instead of cross and dot products.