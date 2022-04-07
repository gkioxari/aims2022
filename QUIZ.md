# Instructions
Please upload a txt file in the form of `firstname_lastname.txt`, e.g. `georgia_gkioxari.txt`. Each line will have your answer to the corresponding question, e.g. `Q1: 1`. Note that there can be multiple correct answers per question, in which case separate your answers with a comma, e.g. `Q1: 1, 2, 3`. Example file:
```
Q1: 1
Q2: 1, 2
Q3: 3, 4
...
```
Upload your answers to this [dropbox link][dropbox] by Sunday, April 18. 

# Test

### Question 1
A mesh is a collection of points without any connectivity between the points
  1. True
  2. False 

### Question 2
Which 3D representation is most efficient when aiming to capture high resolution object shapes?
  1. Voxels
  2. Pointclous 

### Question 3
You have a shape which consists of parts of fine structure. What is the most appropriate 3D representation?
  1. Voxels
  2. Meshes

### Question 4
The chamfer distance measures the distance between
  1. Two voxels
  2. Two pointclouds

### Question 5
[Mesh R-CNN][meshrcnn] predicts 3D object shapes from single 2D images
  1. True
  2. False

### Question 6
In [Mesh R-CNN][meshrcnn], the topology of the predicted object is defined by the mesh refinement branch
  1. True
  2. False

### Question 7
In [Mesh R-CNN][meshrcnn], `vert align` maintains the spatial alignment between the image features and the 3D mesh
  1. True
  2. False

### Question 8
When training models that predict meshes, adding shape regularizers to the objective leads to 
  1. More accurate predictions
  2. Prettier predictions

### Question 9
A distance between two pointclouds can be used as a distance between two meshes via
  1. differentiable mesh rendering
  2. differentiable point sampling on the mesh faces
  3. converting pointclouds and meshes to voxels

### Question 10
Differentiable mesh rendering allows for gradients to propagate back from a 2D loss to a 3D mesh
  1. True
  2. False

### Question 11
In [Mesh R-CNN][meshrcnn], a mesh subdivision followed by a graph convolution results in 
  1. increasing the receptive field
  2. decreasing the receiptive field
  3. none of the above

### Question 12
[NeRF][nerf] maps a `(x,y,z)` point and a `(θ, φ)` viewing direction to a `(r, g, b)` color value and a density `σ` with a sequence of fully connected layers
  1. True
  2. False

### Question 13
[NeRF][nerf] trains a model on hundreds of views from one scene and synthesizes
  1. Novel views of the same scene
  2. Same views of a novel scene
  3. Novel views of a novel scene
  4. All of the above

### Question 14
During training, [NeRF][nerf] requires a set of image views and unknown camera transforms across views
  1. True
  2. False

### Question 15
The Pose embeddings in [NeRF][nerf] map the 3D coordinates `(x,y,z)` to a higher dimensional vector which allows the model to
  1. Train faster
  2. Capture high frequency information

### Question 16
If [NeRF][nerf] shoots `N` rays and samples `P` points on each ray, then how many forward passes through the NeRF model are needed to synthesize a novel view
  1. `N * P * P`
  2. `N * P`
  3. `N`
  4. `P`

### Question 17
Implicit 3D representations model surfaces as zero-crossings of functions. For example surface A is represented as `{p | f~A~(p) = 0}` where `f~A~` is a function. Assume B is a second surface such that `{p | f~B~(p) = 0}`. The function `f` which represents the intersection `A and B` is:
  1. `f(p) = max(f~A~(p), f~B~(p))`
  2. `f(p) = min(f~A~(p), f~B~(p))`  
  3. `f(p) = f~A~(p) - f~B~(p)`

### Question 18
Continuing from Q17, The function `f` which represents the union `A or B` is:
  1. `f(p) = max(f~A~(p), f~B~(p))`
  2. `f(p) = min(f~A~(p), f~B~(p))`  
  3. `f(p) = f~A~(p) - f~B~(p)`

### Question 19
The following implicit function `f(x,y,z) = x^2^ + y^2^ + z^2^ - 1` is a signed distance function (SDF)
  1. True
  2. False

### Question 20
All meshes can be converted to signed distance functions
  1. True
  2. False


[dropbox]: https://www.dropbox.com/request/B7fEOl2NaD2tiTWj5931
[nmr]: https://arxiv.org/abs/1711.07566
[meshrcnn]: https://arxiv.org/abs/1906.02739
[r2n2]: https://arxiv.org/abs/1604.00449
[occnet]: https://arxiv.org/abs/1812.03828
[synsin]: https://arxiv.org/abs/1912.08804
[psg]: https://arxiv.org/abs/1612.00603
[pointnet]: https://arxiv.org/abs/1612.00593
[smpl]: https://files.is.tue.mpg.de/black/papers/SMPL2015_fixed.pdf
[nerf]: https://arxiv.org/abs/2003.08934

