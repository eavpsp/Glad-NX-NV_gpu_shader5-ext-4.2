# GLAD Fork from LIBNX

This repository is a fork of LIBNX's GLAD, updated to support OpenGL 4.4 and the NV GPU Shader 5 extension. This project aims to provide enhanced graphics capabilities for developers working on applications that require the latest OpenGL features and NVIDIA's shader extensions.

## Features

- **OpenGL 4.4 Support**: Access to the latest OpenGL API features, improving performance and visual quality.
- **NV GPU Shader 5 Extension**: Utilize NVIDIA's advanced shader functionalities for more complex and efficient graphics programming.
- **Seamless Integration**: Compatible with existing LIBNX projects, making it easy to upgrade your graphics capabilities without extensive modifications.

## Getting Started

### Prerequisites

- Ensure you have a working build DEVKITPRO environment compatible with LIBNX.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/eavpsp/Glad-NX-NV_gpu_shader5-ext-4.2.git
   cd glad-fork-libnx
   ```

2. Build the project:
   ```bash
   make
   ```

3. Integrate with your existing project, ensuring to update your build scripts to link against the new GLAD library. To do so, repalce the glad header and lib in your libnx portlibs. 
devkitpro/portlibs/switch

## Usage


Refer to the [OpenGL 4.4 documentation](https://registry.khronos.org/OpenGL/specs/gl/glspec44.core.pdf) and [NV GPU Shader 5 extension guide](https://registry.khronos.org/OpenGL/extensions/NV/NV_gpu_shader5.txt) for detailed instructions on using the new features in your applications.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Original GLAD library by LIBNX
- OpenGL and NV GPU Shader 5 documentation and resources

