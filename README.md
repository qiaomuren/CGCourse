# GAMES101: Introduction to Computer Graphics
<div align=center><img src="./imgs/CG.png" width="810" height="10" alt="CG"/></div>

* This is the online course taught by [Ling-Qi Yan](https://sites.cs.ucsb.edu/~lingqi/index.html) in Chinese.
* There are **eight assignments** and **one final project**. All eight assignments only need Eigen, OpenCV except assignment 8.
* My overall grade is **114.81 / 115**. 
* Course Homepage can be found [here](https://sites.cs.ucsb.edu/~lingqi/teaching/games101.html).

## Assignment 1: Rotation and Projection
### Requirements
* Build the model matrix and the perspective projection matrix correctly
* Press the key to rotate the triangle or use the command line to get the rotated image
* [Bonus] Build the model matrix to rotate the triangle around any axis through the origin
### Results (grade: 35 / 35)

## Assignment 2: Triangles and Z-buffering
### Requirements
* Implement triangle rasterization algorithm
* Implement z-buffer algorithm and  draw triangles on the screen in order
* [Bonus] Implement super-sampling algorithm (anti-aliasing)
### Results (grade: 50 / 50)
* Raw result
<div align=center><img src="./imgs/a2_raw.png" width="300" height="300" alt="raw result"/></div>

* Result with MSAA
<div align=center><img src="./imgs/a2_msaa.png" width="300" height="300" alt="raw result with msaa"/></div>


## Assignment 3: Pipeline and Shading
### Requirements
* Interpolate colors, normal vectors, texture coordinates, and position correctly
* Implement Blinn-phong reflection model correctly
* Implement Texture Mapping correctly
* Implement Bump mapping and Displacement mapping correctly
* [Bonus] Try more models: Find other available .obj files and render them
* [Bonus] Implement bilinear texture interpolation
### Results (grade: 58 / 58)
* The results from left to right are normal mapping, bump mapping, texture mapping, displacement mapping and Blinn-phong reflection model. 
<div align=center><img src="./imgs/a3.png" width="555" height="225" alt="a3"/></div>

* Results w/o bilinear texture interpolation
<div align=center><img src="./imgs/a3_bi.png" width="500" height="190" alt="a3 bi"/></div>



