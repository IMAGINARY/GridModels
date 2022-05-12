# Text in the 10-minute museum


## Grid Models

Even with the fastest supercomputers we cannot model all climate processes of all regions of the Earth in all details.

To overcome this issue, we split up the Earth into small “grid cells” and compute the climate processes for these cells in parallel. We connect the cell calculations to obtain a global result.

The size of the grid cells is called the resolution of the grid. A common size is 100 square kilometers of Earth surface per cell.

There are many criteria to pick a grid for our model. Sometimes it’s better if all cells have a similar size, sometimes four-sided cells are preferable. Usually a regular arrangement simplifies calculations.




### Latitude Longitude Grid
The classical one, which has the problem that cells get smaller towards the two poles.

### Cubed Sphere Grid
Built by “inflating” a cube. Its cells get distorted where the cube’s edges meet.

### Octahedral Gaussian Grid
Cells are triangles with similar size. Their angles, whoever, are not always the same.

### Hexagonal Icosahedron Grid
Can you find cells with five sides? This makes listing neighbouring cells tricky.
