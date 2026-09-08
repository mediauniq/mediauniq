# <img width="48" height="48" alt="image" src="https://github.com/user-attachments/assets/3ed3ea57-4d17-4e73-a29b-c2dcae386e7f" /> PRND — Media Randomizer / 媒体随机化工具

![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-blue) ![Version](https://img.shields.io/badge/version-v1.6-success) ![Interface](https://img.shields.io/badge/interface-EN%20%7C%20RU%20%7C%20ZH-orange) ![Engine](https://img.shields.io/badge/engine-FFmpeg-informational)

**PRND Media Randomizer** 让您发布的每个文件都保持唯一。一个桌面工具即可随机化**图片、视频和音频**——几何形状、颜色、叠加元素、元数据、文件日期和名称。非常适合批量私信 / SMM 营销场景（相同附件容易触发限制），也是通过 Telegram PRIME 群发触达更多受众的理想解决方案。

> 本说明还提供其他语言版本：
> **[EN — English](https://github.com/mediauniq/mediauniq/README.md)** · **[RU — Русский](https://github.com/mediauniq/mediauniq/README_RU.md)**

----
<img width="768" alt="MediaUniq" src="https://github.com/user-attachments/assets/f2b11cf9-c97e-4caf-accc-1cfd41b511fa" />

----

## ✨ 核心亮点

| | |
|---|---|
| **3 个媒体模块** | 图片、视频、音频集于一窗——各自拥有完整的随机化功能 |
| **任意格式互转** | 导入 MP3，导出随机化的 OGG/OPUS/M4A——现代即时通讯软件常用的格式 |
| **全方位唯一化** | 随机效果、EXIF/标签重写、随机文件日期、5 种命名规则 |
| **批量优先** | 指向文件夹——每个文件生成 N 个随机命名的副本，绝不覆盖 |
| **实时预览** | 运行前先看样本：MIN/MAX 边界、自动预览、带音量的试听 |
| **隐私保护** | 所有处理均在本地完成（FFmpeg/Pillow）——媒体文件永不上传 |
| **多语言界面** | English、Русский、简体中文 · 11 种主题 · 可调字体大小与界面缩放 |

----
## 🖼️ 「图片」标签页

支持的输入格式：`.jpg` `.jpeg` `.png` `.tif` `.tiff`

| 功能 | 说明 |
|---|---|
| 随机几何 | 缩放、旋转（双向）、边缘裁剪、圆角 |
| 随机颜色 | 对比度、色彩/饱和度、亮度、清晰度、模糊、色调 |
| RGB 像素化 | 随机处理次数 |
| 导出质量 | 随机 JPEG 质量范围 |
| 边框 | 随机颜色和粗细 |
| 文字叠加 | 多行文字、字体、大小、颜色/随机颜色、位置、不透明度、旋转、边距 |
| 水印 | 图片叠加：大小、不透明度、旋转、边距、12 种位置变体（含手动 X/Y 百分比） |
| EXIF 元数据 | 完全清除或随机化（相机、软件、地理位置等） |
| 文件日期 | 随机修改日期 |
| 批量模式 | 文件夹输入，每文件 N 个副本 |
| 实时预览 | 以当前设置渲染样本，MIN/MAX 边界 |

----
## 🎬 「视频」标签页

支持的输入格式：`.mp4` `.mov` `.mkv` `.avi` `.webm` `.m4v` `.mpg` `.mpeg` `.ts` `.wmv` `.gif`

| 功能 | 说明 |
|---|---|
| 裁剪 | 从开头和结尾随机截取 |
| 运动 | 随机速度、FPS 抖动、镜像、旋转、缩放 |
| 颜色 | 随机亮度、对比度、饱和度、伽马 |
| 音轨 | 随机音量范围、静音 |
| 文字叠加 | 多行、字体、大小、不透明度、旋转、边距、淡入/淡出、随机显示窗口 |
| 边框 | 随机颜色和粗细 |
| 背景 | 随机纯色或图片居中叠加 |
| 元数据 | 随机 MP4 标签、随机文件日期 |
| 编码 | CRF 范围、预设、硬件加速、仅元数据的流复制模式 |
| GIF 支持 | 动图 GIF 输入——随机化 GIF 输出 |
| 预览 | 当前滤镜链的逐帧预览 |

----
## 🎵 「音频」标签页

支持的输入格式：`.mp3` `.wav` `.ogg` `.opus` `.m4a` `.aac` `.flac` `.wma` `.aiff`
输出格式：`.mp3` `.ogg` `.opus` `.m4a` `.aac` `.wav` `.flac` `.wma`

| 功能 | 说明 |
|---|---|
| 格式转换器 | 任意输入格式转换为任意输出格式（例如输入 MP3，输出用于即时通讯软件的随机化 OGG） |
| 速度 | 随机播放速度 |
| 音高 | 随机半音偏移，保持时长 |
| 音量 | 随机响度范围 |
| 均衡器 | 随机低音 / 高音 |
| 淡入淡出 | 随机淡入与淡出 |
| 比特率 | 有损格式的随机比特率 |
| 标签 | 随机化 title/artist/album/genre/date 或完全清除 |
| 文件日期 | 随机修改日期 |
| 试听 | 渲染应用当前效果的前 10 秒并播放——MIN/MAX、自动预览、音量滑块 |

----
## 🧩 通用功能

| 功能 | 说明 |
|---|---|
| 命名规则 | 5 种全局模板：完全随机名称（默认）/ 原始名称 + 随机部分 / 原始名称 + 序号 + 随机部分 / 原始名称 + 序号 / 日期时间 + 随机部分。绝不覆盖已有文件 |
| 界面 | 11 种主题，EN/RU/ZH，可调字体大小与界面缩放 |
| 设置 | 每个标签页的状态自动保存；每页均有「恢复上次」/「推荐」/「重置」 |
| 引擎 | FFmpeg 在首次运行时自动下载 |
| 更新与支持 | 免费更新，在线支持 |

----
## 🚀 快速开始

1. 下载最新版本，解压并运行。
2. 在授权窗口内直接申请免费演示密钥。
3. 选择标签页，指定源文件或文件夹及输出文件夹，调整随机范围。
4. 点击 **RANDOMIZE**。

----
## 🔑 试用期与许可证

我们提供 24 小时**免费试用期**：1,000 个随机化文件的额度，供您在购买前测试并确认系统效率。申请演示密钥的按钮位于软件内部。

试用期结束后，本产品提供多种付费订阅方案：

| 许可证 | 额度 |
|---|---|
| 月度 | 20,000 个随机化文件 |
| 年度 | 50,000 个随机化文件 |
| 永久 | 终身无限量 |

----
## 📥 下载

- [始终最新版本](https://mediauniq.com/downloads)

----
## 🎥 视频指南

- [YouTube](https://youtu.be/)

----
## 📸 截图

<img width="256" alt="MediaUniq" src="https://github.com/user-attachments/assets/19279878-2fd4-48a2-bda6-5a9a8efa1576" />
<img width="256" alt="MediaUniq" src="https://github.com/user-attachments/assets/0de8075e-121c-4057-98a8-51fc7112a51d" />
<img width="256" alt="MediaUniq" src="https://github.com/user-attachments/assets/af2e7c96-9e53-4d30-b892-2221a81cd7bc" />

----
## 💬 联系方式

| 渠道 | 联系 |
|---|---|
| Web | https://mediauniq.com/ |
| Email | manager[@]mediauniq.com |
| Telegram | [Send message](https://mediauniq.com/telegram-contact) |
| Discord | [Send message](https://mediauniq.com/discord-contact) |
| Element | [Send message](https://mediauniq.com/element-contact) |

----
## ☕ 捐赠

* [请我们喝杯咖啡 :)](https://nowpayments.io/donation/mcv)
* 谢谢您！

----
