# v0.0.6

- 自定义 User-Agent
- webview for android

# v0.0.5

2025-02-09

- flutter 3.27.4
- 修复一处数据库初始化错误
- 优化数据库在系统中的存储位置
  - 使用 getApplicationSupportDirectory() 获取存储路径，如果失败当 HOME
    变量存在就存储到 $HOME/.local/share/com.github.selene201226.anime
  - windows: C:\Users\用户名\AppData\Roaming\com.github.selene201226\anime
  - linux: $HOME/.local/share/com.github.selene201226.anime
- 为 linux 增加 AppImage 支持
- 退出 app 时添加确认，避免误触遥控器退出 app
- 为播放器 ui 添加背景避免画面和 ui 配色太接近导致 ui 看不清

# v0.0.4

2025-01-06

- 修复 v0.0.3 引起的观看记录错误

# v0.0.3

2025-01-05

- 修复桌面平台 全屏 bug
- 修复影集播放多个视频返回后的页面记录没有更新
- 为时间表和观影历史两个页面中的动画添加连载信息

# v0.0.2

2025-01-04

- flutter 3.27.1
- 修復一些 bug
- 优化转拼音效率
- 支持 linux
- 支持 windows
- 增加缓存

# v0.0.1

2025-01-01

- flutter 3.19.1
- 支持 android
- 支持 android tv
