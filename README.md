##### I will continue updating this project
<hr>

# Iolive

> Originally made by wahyuandhika, I'm just actually a library updater.

<img src="https://i.imgur.com/gTPARWp.png" width="100" height="100"/>

[![License](https://img.shields.io/github/license/Rabbit0w0/Iolive)](https://github.com/Rabbit0w0/Iolive/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/Rabbit0w0/Iolive.svg)](https://github.com/Rabbit0w0/Iolive/commits/main)

[Iolive](https://github.com/Rabbit0w0/Iolive) is an application for displaying Live2D model with face tracking support.

## TODOs
- Add more customizable things
- Remember window size and model position
- Improve performance
- Gather stars
Check out this repo next month! (December, 2022)

## Build
this project can be built using MSVC 141+, and cmake version > 3.13

## Iolive Third Party Libraries
* [GLFW](https://github.com/glfw/glfw)
* [GLEW](http://glew.sourceforge.net/)
* [Dear ImGui](https://github.com/ocornut/imgui/)
* [RapidJSON](https://github.com/Tencent/rapidjson/)
* [CubismNativeFramework](https://github.com/Live2D/CubismNativeFramework) (Modified) (CubismMotionManager.hpp, CubismModel.hpp)
* [Live2DCubismCore](https://www.live2d.com/en/download/cubism-sdk/download-native/)<br/>

For more information, look in the [Vendor/](https://github.com/Rabbit0w0/Iolive/tree/main/Iolive/Vendor) directory

## About Ioface Project
Ioface is Iolive's face tracking tools which is built on [OpenCV 3.2.0](https://github.com/opencv/opencv/tree/3.2.0) and IntraFace.

The original source of IntraFace library is unknown [*seems to have been deleted](http://www.humansensing.cs.cmu.edu/intraface)<br/>
but there is still a research paper about it, see: [IntraFace Final](https://www.researchgate.net/publication/280298368_IntraFace).<br/>
Ioface using IntraFace library from [@genshengye](https://github.com/genshengye) in his [repository](https://github.com/genshengye/IntraFace/)

## License
This project based on Cubism Core & CubismNativeFramework, and under Live2D license agreement, see:
* [CubismNativeFramework License](https://github.com/Live2D/CubismNativeFramework/blob/develop/LICENSE.md)
* [Live2D Open Software License Agreement](https://www.live2d.com/eula/live2d-open-software-license-agreement_en.html)
* [Live2D Proprietary Software License Agreement](https://www.live2d.com/eula/live2d-proprietary-software-license-agreement_en.html)

Iolive is open sourced software, licensed under [GPL v3.0](https://github.com/Rabbit0w0/Iolive/blob/main/LICENSE)
