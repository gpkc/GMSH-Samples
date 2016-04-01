# GMSH Samples
A few samples of Gmsh meshes and geometries for using with Finite Volume solvers.

## Installing GMSH
To open those samples, you need to have a Gmsh binary.
* For standalone binaries (Windows included), go to [Gmsh's website](gmsh.info), extract them and run.
* For Debian-based Linux distributions, use `apt-get install gmsh`. Notice that this may not give you the latest binaries. If you want those, download from the official website.

## Running
If you already have Gmsh installed, you can follow those steps to run the software:
* From Windows, just run gmsh.exe
* From Linux, if you have installed from the repository, you can run `$ gmsh` from the terminal.
* From Linux, if you have downloaded the binaries, go to the extracted folder and run `$ ./gmsh`.
To open a given mesh, you can use the contextual menu File -> Open, or if you're using a terminal, you can pass the mesh/geometry file as argument to gmsh (for example, `$ gmsh mesh1.msh`).
