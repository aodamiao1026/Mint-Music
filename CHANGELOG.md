# Changelog

## [Unreleased]

### iOS 适配
- Runner 与全部 Pods 的 iOS 部署目标提升至 15.0（Xcode 27 最低要求，Podfile post_install 自动抬升旧 Pods）
- 下载目录默认值改为平台自适应：iOS 使用应用沙盒 Documents/MintMusic，Android 保持公共 Music 目录
- 修复 Xcode 27 下 actool "Failed to write to CAR" 报错的排查指引（清理 DerivedData）

## [1.0.1] - 2026-08-14

### 新增
- 多音源在线音乐：网易云、QQ音乐、酷狗、酷我、咪咕
- 跨音源自动换源与音质切换
- AMLL Apple Music 风格逐字歌词
- 本地音乐扫描与播放
- 下载中心（文件名格式、标签写入、仅 WiFi 下载）
- 音效增强：均衡器、低音增强、环绕音效、声道平衡
- LX 风格 JS 音源插件导入
- 浅色 / 深色主题与主题色自定义
- 播放记忆、启动自动续播、倍速播放

### 开源
- 首次公开发布，添加 MIT 许可证、README 与 CI
