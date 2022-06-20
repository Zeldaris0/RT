42-RT: Ray Tracing engine from scratch (1337 school project)

![image](https://user-images.githubusercontent.com/63746115/174649901-201d565f-4f77-4100-b120-7e4373f6205e.png)


1. Overview

The project implements a Ray Tracing engine from scratch in C and OpenCL for rendering volumetric figures. The engine supports the following features:

5 simple figures: plane, sphere, cylinder, [capped] cone, box + 1 complex figure: wineglass;
4 operations that can be applied to simple objects to construct complex ones: union, intersection, difference, clipping;
4 light source types: ambient, point, parallel, spot;
Reflective and transparent materials;
Camera movement in 3 dimensions with variable FOV;

![image](https://user-images.githubusercontent.com/63746115/174650216-77c5fc11-8679-4040-808b-2e990efdd10a.png)



2. Compilation
Requires SDL2, OpenCL

Linux: SDL2 headers should be located in /usr/include/SDL2

Mac OS: local version of SDL2 is included in ./frameworks

make to compile ./RT
make clean to delete .o files
make fclean to delete .o files and ./RT
make re to delete everything and recompile

![image](https://user-images.githubusercontent.com/63746115/174650058-5a47e111-ec8b-44e9-bae8-e0d618187bfe.png)

![image](https://user-images.githubusercontent.com/63746115/174650075-2fc08458-7981-4cbd-9dbe-0fa3bee07437.png)

![image](https://user-images.githubusercontent.com/63746115/174650234-f8487e47-dcb7-47dc-9c41-cdacb64d4df8.png)

