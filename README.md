# 3D--recursive-ray-tracing
This project is a comprehensive introduction to 3D Computer Graphics developed during my Master’s at the University of Bordeaux. I implemented a recursive ray tracing engine from scratch to understand the mathematical and logical foundations of image synthesis.

Key Features Implemented:

    Primary Ray Generation: Simulating a pinhole camera model to cast rays through an image plane.

    Geometric Intersections: Analytical solutions for ray-sphere and ray-plane intersections (solving quadratic and linear equations).

    Local Illumination: Implementation of the Lambertian (Diffuse) and Phong reflection models, including specular highlights.

    Secondary Rays: * Shadow Rays: Implementing light visibility tests with bias management (epsilon) to avoid self-intersection.

        Recursive Whitted-style Reflections: Simulating mirror-like surfaces with multiple bounces.

    Normal Visualization: A dedicated integrator to debug and visualize surface orientations.
