# 视频文件说明

## 文件命名规范

### 15个游戏视频
- **位置**: `games_15/`
- **命名**: `game_01.mp4`, `game_02.mp4`, ..., `game_15.mp4`
- **说明**: 共15个视频文件，展示15个不同游戏的流畅游戏视频

### 模型+人类对比视频
- **位置**: `models_vs_human/`
- **结构**: 
  ```
  models_vs_human/
  ├── model1/
  │   ├── clip_01.mp4  (Baba Is You)
  │   ├── clip_02.mp4  (Angry Birds)
  │   ├── clip_03.mp4  (Scene Investigators)
  │   ├── clip_04.mp4  (Plants vs. Zombies)
  │   └── clip_05.mp4  (Red Dead Redemption 2)
  ├── model2/
  │   └── (同上5个文件)
  └── human/
      └── (同上5个文件)
  ```
- **说明**: 
  - 2个模型 + 1个人类，共15个视频（3 × 5）
  - 5行对应游戏顺序：Baba Is You, Angry Birds, Scene Investigators, Plants vs. Zombies, Red Dead Redemption 2

### VR对比视频
- **位置**: `vr_comparison/`
- **文件**: 
  - `before.mp4`, `after.mp4`: 第1组 Before/After VR
  - `before_2.mp4`, `after_2.mp4`: 第2组
  - `before_3.mp4`, `after_3.mp4`: 第3组
- **说明**: 共3组对比，每组左右分屏展示 Before VR / After VR

## 视频要求

- **格式**: MP4 (推荐使用 H.264 编码)
- **分辨率**: 建议 1920×1080 或更高
- **帧率**: 建议 30fps 或 60fps
- **文件大小**: 建议每个视频文件不超过 50MB（可根据实际需要调整）

## 占位符

如果视频文件尚未准备好，页面会显示空的视频播放器。您可以：
1. 先使用占位符视频进行测试
2. 准备好实际视频后，按照命名规范放入对应文件夹即可
