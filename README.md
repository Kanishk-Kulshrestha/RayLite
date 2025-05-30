# RayLite — Lightweight Ray Tracer in C++

**RayLite** is a minimal and efficient ray tracer written from scratch in C++. It implements fundamental ray tracing concepts including lighting, shading, and reflections, with a focus on performance and clarity.

## Features

- Recursive ray tracing with reflection
- Shadows and diffuse lighting using anti aliasing
- Sphere rendering with simple material system
- Optimized for low memory usage and speed
- Outputs rendered image as a `.ppm` file


## How to Run

### Prerequisites
- C++ compiler (e.g., `g++`)
- Command-line terminal (Windows, Linux, or Mac)

### Build and Execute

```bash
git clone https://github.com/Kanishk-Kulshrestha/RayLite.git
cd RayLite
g++ -o output.exe main.cpp
output.exe > image.ppm
```
