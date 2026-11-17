# Vulkan Pyramid

Please go visit:
  https://github.com/zhiyuz2013/Towardlight-VukanGLFW-triangle
for the source code.

A small native C++ sample that draws a colored 3D pyramid using the Vulkan API.
GLFW is used only to create the window and receive window events; rendering is
performed entirely with Vulkan (there is no OpenGL renderer).

## Requirements

- Linux with a working Vulkan driver and desktop session
- CMake 3.20 or newer
- A C++17 compiler
- Vulkan SDK headers/loader
- GLFW 3.3 or newer
- GLM
- `glslangValidator`

On Ubuntu, the development packages can be installed with:

```sh
sudo apt install build-essential cmake libvulkan-dev libglfw3-dev libglm-dev glslang-tools
```

Install a Vulkan driver for your GPU as well. For Mesa-based Intel/AMD GPUs,
`mesa-vulkan-drivers` provides one; NVIDIA systems need the matching proprietary
driver. `vulkan-tools` is optional but provides `vulkaninfo` for diagnostics.

## Demo

https://github.com/user-attachments/assets/cf085ef8-42c2-4d31-ad91-519156391cd9


<img width="640" height="400" alt="demo" src="https://github.com/user-attachments/assets/0656b10e-492d-4ee6-ae4e-ae8a102b7f5a" />
