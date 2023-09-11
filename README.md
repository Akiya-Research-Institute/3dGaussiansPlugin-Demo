# [3D Gaussians Plugin](https://vrlab.akiya-souken.co.jp/en/products/threedgaussianplugin/) Demo Project

## Download packaged build

Packaged build of this demo project in EXE format is available [here](https://s3.ap-northeast-1.wasabisys.com/whisperrealtime/3dGaussiansPluginDemo-v1.0.zip)

## System Requirements

- Windows 10 64bit
- Unreal Engine 5.3.0
- [3D Gaussians Plugin] 1.0.0
- GPU which support DirectX 12

## Setup

1. Clone this repository: `git clone https://github.com/Akiya-Research-Institute/3dGaussiansPlugin-Demo`
2. Open `3dGaussiansPlugin-Demo/ThreeDGaussiansDemo.uproject`
3. Click `Content Drawer > Add > Add Feature or Content Pack...`
4. Select `Third Person` on Blueprint tab and click `Add to Project`
5. Click `Play` on Unreal Editor.
6. Press `Tab` to change map. Press `F` to show FPS.

## Content explanation

- `Content/ThreeDGaussians/DemoMaps`: Maps for demo scenes.
- `Content/ThreeDGaussians/Bicycle`: Imported data of training result of 3D Gaussian Splatting for Bicycle scene.
- `Content/ThreeDGaussians/Garden`: Imported data of training result of 3D Gaussian Splatting for Garden scene.
- `Content/ThreeDGaussians/DemoBP`: BP to define keyboard inputs for this project.
- `Content/ThreeDGaussians/DemoInput`: IMC to define keyboard inputs for this project.

## Third party license notice

The demo software is built using the following open source software:

- [3d-gaussian-splatting](https://github.com/WangFeng18/3d-gaussian-splatting) (An unofficial Implementation)
- [Mip-NeRF 360](https://jonbarron.info/mipnerf360/)