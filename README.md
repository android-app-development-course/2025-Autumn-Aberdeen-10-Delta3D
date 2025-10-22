# 3D 物体建模移动应用

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 项目简介

这是一个基于移动端的 3D 物体建模应用，用户可以通过手机摄像头拍摄物体视频，实现一键上传到云端进行 3D 重建。应用支持用户登录、模型交互、导出分享以及社区互动，旨在为用户提供简单、高效的 3D 建模体验。核心技术包括视频处理、Instant-NGP 神经辐射场重建等，适用于 AR、3D 打印和内容创作场景。

项目目前处于开发阶段，已完成部分云端建模核心链路验证。


## 核心功能

1. **用户登录与注册**：用户可自定义用户名和密码，通过云端同步机制，实现建模数据、收藏记录与社区互动的跨设备无缝衔接。

2. **视频采集与上传**：使用手机摄像头环绕拍摄物体，应用自动检测是否完成一周拍摄，确保视频适合 3D 重建。一键上传至云端，支持从相册导入视频。

3. **云端视频重建与 3D 建模**：连接服务器进行视频抽帧、相机位姿估计（COLMAP）和稀疏/稠密重建（Instant-NGP），自动生成 3D 点云与网格模型。

4. **3D 模型查看与交互**：预览生成的 3D 模型，支持旋转、缩放、自由视角切换，并模拟光照效果，提供移动端流畅视觉体验。

5. **模型管理**：支持命名、分类、标签管理、收藏与删除，便于用户整理和检索。

6. **模型导出与多平台分享**：导出为常见格式（如 .obj、.glb、.ply），可导入电脑编辑，或一键分享至社交媒体、云盘、AR 平台或 3D 社区。

7. **社区分享与互动**：内置 3D 模型社区，支持发布、浏览、收藏他人模型，包含点赞、评论、标签与搜索功能。

## 技术实现

### 1. 视频处理与 3D 建模
![3D modeling](images/image1.png)

### 2. 3D 建模互动

![Model interaction](images/image2.png)
### 3. 模型导出与分享

![Model export](images/image3.png)


## 截图展示

- **拍摄生成**  
  ![Create model](images/image4.png)

- **模型预览**  
  ![Model Preview](images/image6.png)

- **obj导出**  
  ![Community Sharing](images/image5.png)


## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。

## 联系

- Issues： [GitHub Issues](https://github.com/android-app-development-course/2025-Autumn-Aberdeen-10-Delta3D/issues)
