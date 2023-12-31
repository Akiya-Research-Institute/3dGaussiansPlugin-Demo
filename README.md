# [3D Gaussians Plugin](https://vrlab.akiya-souken.co.jp/en/products/threedgaussianplugin/) Demo Project

[![Youtube demo](http://img.youtube.com/vi/xjIJklDqJdE/0.jpg)](https://www.youtube.com/watch?v=xjIJklDqJdE)

## Download packaged build

Packaged build of this demo project in EXE format is available [here](https://s3.ap-northeast-1.wasabisys.com/whisperrealtime/3dGaussiansPluginDemo-v1.0.zip)

## System Requirements

- Windows 10 64bit
- Unreal Engine 5.3.0
- 3D Gaussians Plugin 1.0
- GPU which support DirectX 12

## Setup

1. Clone this repository: `git clone https://github.com/Akiya-Research-Institute/3dGaussiansPlugin-Demo`
2. Open `3dGaussiansPlugin-Demo/ThreeDGaussiansDemo.uproject`
3. Click `Content Drawer > Add > Add Feature or Content Pack...`
4. Select `Third Person` on Blueprint tab and click `Add to Project`
5. Click `Play` on Unreal Editor.
6. Press `Tab` to change map. Press `F` to show FPS.

## How to use demo

Demo includes "Garden" and "Bicycle" scenes using [Mip-NeRF 360](https://jonbarron.info/mipnerf360/) data.

- Move: WASD keys + Mouse
- Change scenes: Tab key
- Show FPS: F key
- Quit demo: ESC key

## Content details

- `Content/ThreeDGaussians/DemoMaps`: Maps for demo scenes.
- `Content/ThreeDGaussians/DemoData/Bicycle`: Imported data of training result of 3D Gaussian Splatting for Bicycle scene. Split by morton code.
- `Content/ThreeDGaussians/DemoData/Garden`: Imported data of training result of 3D Gaussian Splatting for Garden scene. Split by the distance.
- `Content/ThreeDGaussians/DemoInput`: BPs to define keyboard inputs for this project.