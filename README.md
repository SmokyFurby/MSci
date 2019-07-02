# MSci

The purpose of the Mathematica notebooks in this repository is to build up the governing equations for the model, find a solution representing the travelling waves and to create six different animations which display rotational and elastic waves. Although comments are provided throughout the source code, a brief outline of the notebooks is given in this readme file.

1) euler_equations.nb

First, we build up the full model in the notebook. However, the explicit equations would be too complicated to display explicitly. Instead, we make assumptions on both travelling waves, leaving us with two PDEs.

2) matrix_wave.nb

The aim of this notebook is to substitute a plane wave ansatz into the PDE to obtain a solution for the elastic and rotational waves.

3) The other notebooks

The purpose of these Mathematica notebooks is to create six different animations which display rotational and elastic waves. There is one notebook for each animation.

Each animation is created by exporting a table of 25 frames in GIF format (or 28 for solitons.nb). Frames consist of six rings, where each ring has a different colour and equilibrium position. The rings are given stripy patterns, making the rotations easier to see. Figure 1 consists of eight of the frames from the animation rota_trans.gif.
Two functions, long and trans, are defined so they represent longitudinal and transversal elastic waves respectively. The rotations of material points are represented by defining the function rotate.

To produce an animation from one of the notebooks, you can run all the cells in the notebook simultaneously.
