# Data download
French territory LIDAR point clouds are downloaded from https://geoservices.ign.fr/lidarhd.

# Data preparation
1- Point cloud is imported into CloudCompare\
2- Select laz file\
3- Edit > Normals > Compute\
4- Select laz file\
5- Plugins\
6- PoissonRecon (Octree depth = 11)\
7- Select original laz file and Mesh\
8- Cloud registration\
9- Select original laz file, Edit > Colors > From Scalar Fields > Chose colors\
10- Select original laz file and Mesh\
11- Edit > Colors > Interpolate from another entity\
12- Select Mesh nd File > Save as FBX binary\
13- Import file in blender and export as glTF Separate
