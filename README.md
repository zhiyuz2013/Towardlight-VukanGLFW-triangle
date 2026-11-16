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

<img width="1861" height="1131" alt="image" src="https://github.com/user-attachments/assets/7706fbfe-2afb-4cd3-974c-8a973f39c937" />
