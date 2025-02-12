# Cuda Voxel Raytracing
This is a realtime voxel ray tracing prototype. I aim to make it as powerful as possible (concerning speed and quality). It should be able to render millions of voxels, maybe even of different sizes (but still layed out in an axis aligned grid). I am going to use rendering techniques such as raytracing and denoising, but nothing will be rasterized (except for UI elements). The engine should be capable of simulating GI, direct lighting (shadows), reflections and maybe even refractions.

# Milestones
* 6.1.2022: Created working project with CMake. I use C++ 17, CUDA, GLFW, GLEW and GLM. Also set up the basic engine structure and important Cuda and OpenGL stuff like a Window class and Cuda-OpenGL interoperability (displaying pixel data from Cuda in an GLFW window).