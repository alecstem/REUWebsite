# Pseudocode

## This is where we will have our process broken down into pseudocode 


### Import point cloud data:\

Type in lats(1) and longs(1)\
Type in lats(2) and long(2)\
Search API for Databases in that region\
Get json data for these databases\
  Check all the files in that database\
  Download first file in database\
  
Convert downloaded laz file to las file\
Convert las file to ascii file\

### Generate 2D grid:\

Break up each x, y coridnates per height from ascii file\

### Generrate buffer for each height:\

Generrate buffer for each layer using BFS\

### Combine 2D grids to form a 3D matrix:\

Combine 2D grids to form a 3D matrix\

### Run path planning algorithm:\

Run adapted A* on the layered model\
  Form a path and produce points for the path\
  
### Convert best path to pointclouds:\

Convert best path points to point cloud points\

### Convert point cloud to GPS:\

Convert point cloud points to GPS coridnates\

### Send path to UAV:\

Send GPS coridnates to drone for flight path\

### Collision avoidence:\

While not at end point\
  Constantly calculate A*\
  If LiDAR scanner finds obsticle\
    create new best path\

  Avoid obsticle and reconnect with orginal path\

