# MSci

The purpose of the Mathematica notebooks in this repository is to create six different animations which display rotational and elastic waves. Although comments are provided throughout the source code, a brief outline of the code the is given in this readme file.

Each animation is created by exporting a table of 25 frames in GIF format (or 28 for solitons.nb). Frames consist of six rings, where each ring has a different colour and equilibrium position. The rings are given stripy patterns, making the rotations easier to see. Figure 1 consists of eight of the frames from the animation rota_trans.gif.
Two functions, long and trans, are defined so they represent longitudinal and transversal elastic waves respectively. The rotations of material points are represented by defining the function rotate.

To produce an animation from one of the notebooks, you can run all the cells in notebook simultaneously.
