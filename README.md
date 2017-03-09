# mCoupler
mCoupler is a mesh coupler for multiphysics applications. Its main functionality is to transfer solution vaiables between different meshes in 1-D, 2-D, and 3-D, including curves and surfaces. The meshes in general are nonmatching, in that they can have elements of different sizes and shapes. The meshes may occupy the same or partially overlapping domains. 

Notable features include:
 - high accuracy and conservation
 - treatment of mismatching curves and surfaces
 - treatment of mismatch boundaries
 - support of different discretization methods, including finite element, finite volume, and even meshless methods
 - high-order methods, including FEM, DG, and AES-FEM supported
 - treatment of discontinuities in solutions (and in curves and surfaces)
 - efficient C code with high-level Python API
 - multithreaded implementation of solution transfer
