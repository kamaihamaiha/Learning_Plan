## 音视频开发

- 知识树
- 课程
- 开源项目
- 行业大佬
- [Android 官方文档](https://developer.android.com/guide/topics/media)

---

### 知识树

1. 音视频基础知识
2. C 语言
3. C ++  语言
4. FFmpeg
5. Linux
6. WebRTC
7. Android 上的音视频 API
8. JNI / NDK
9. OpenGL 渲染
10. libyuv
11. Vulkan

---

### 课程

- [音视频小白系统入门(初级)](https://coding.imooc.com/class/415.html)
- [FFmpeg音视频核心技术全面精讲+实战(进阶)](https://coding.imooc.com/learn/list/279.html)
- [实时互动直播技术（进阶）](https://coding.imooc.com/class/329.html)
- [企业级流媒体服务器设计与开发（高级）](https://coding.imooc.com/class/387.html)
- 《FFmpeg 从入门到精通》
- Android 音视频开发任务列表

---

### 开源项目

- [Grafika](https://github.com/google/grafika)
- [Android-gpuimage](https://github.com/cats-oss/android-gpuimage)
- [AudioVideoRecordingSample](http://AudioVideoRecordingSample)
- [ijkplayer](https://github.com/bilibili/ijkplayer)
- [ExoPlayer](https://github.com/google/ExoPlayer)

---

### 行业大佬

- glums（赵颖）
  - [Github](https://github.com/glumes)
  - [博客](https://www.glumes.com/)
  - [B 站](https://space.bilibili.com/105478237)
  - 支持内推 
- 李超
- 何俊林
- 周俊杰
  - [极客时间](https://time.geekbang.org/column/article/88846)
  - 负责微信的音视频开发工作
- Jhuster
  - [博客](https://blog.51cto.com/ticktick/1956269)
  - 字节跳动音视频架构师
- [雷霄骅](https://blog.csdn.net/leixiaohua1020)

---

### 入门到提高---任务列表

1. 在 Android 平台绘制一张图片，使用至少 3 种不同的 API，ImageView，SurfaceView，自定义 View
2. 在 Android 平台使用 AudioRecord 和 AudioTrack API 完成音频 PCM 数据的采集和播放，并实现读写音频 wav 文件
3. 在 Android 平台使用 Camera API 进行视频的采集，分别使用 SurfaceView、TextureView 来预览 Camera 数据，取到 NV21 的数据回调
4. 学习 Android 平台的 MediaExtractor 和 MediaMuxer API，知道如何解析和封装 mp4 文件
5. 学习 Android 平台 OpenGL ES API，了解 OpenGL 开发的基本流程，使用 OpenGL 绘制一个三角形
6. 学习 Android 平台 OpenGL ES API，学习纹理绘制，能够使用 OpenGL 显示一张图片
7. 学习 MediaCodec API，完成音频 AAC 硬编、硬解
8. 学习 MediaCodec API，完成视频 H.264 的硬编、硬解
9. 串联整个音视频录制流程，完成音视频的采集、编码、封包成 mp4 输出
10. 串联整个音视频播放流程，完成 mp4 的解析、音视频的解码、播放和渲染
11. 进一步学习 OpenGL，了解如何实现视频的剪裁、旋转、水印、滤镜，并学习 OpenGL 高级特性，如：VBO，VAO，FBO 等等
12. 学习 Android 图形图像架构，能够使用 GLSurfaceviw 绘制 Camera 预览画面
13. 深入研究音视频相关的网络协议，如 rtmp，hls，以及封包格式，如：flv，mp4
14. 深入学习一些音视频领域的开源项目，如 webrtc，ffmpeg，ijkplayer，librtmp 等等
15. 将 ffmpeg 库移植到 Android 平台，结合上面积累的经验，编写一款简易的音视频播放器
16. 将 x264 库移植到 Android 平台，结合上面积累的经验，完成视频数据 H264 软编功能
17. 将 librtmp 库移植到 Android 平台，结合上面积累的经验，完成 Android RTMP 推流功能
18. 上面积累的经验，做一款短视频 APP，完成如：断点拍摄、添加水印、本地转码、视频剪辑、视频拼接、MV 特效等功能