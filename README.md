This library so far mainly provides the means to optimize the rotation
of a Manhattan Frame (MF) given surface normal associations. 


### Dependencies

This code depends on the following other libraries and was tested under Ubuntu
14.04. 
- pcl 1.7 (and vtk 5.8)
- Opencv 2 (2.3.1)
- Eigen3 (3.0.5) 
- cuda 5.5 or 6.5 
- Boost (1.52)

The GPU kernels were tested on a Nvidia Quadro K2000M with compute
capability 3.0.

### Library
*libmmf.so* collects all the cuda code into one shared library. The rest
of the code is in the form of header files.

