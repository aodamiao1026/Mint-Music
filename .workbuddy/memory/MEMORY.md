# MintMusic 项目备忘

- 音乐播放器，Flutter + Riverpod + go_router，原为 Android 单平台，2026-10 起支持 iOS
- iOS 原生通道在 ios/Runner/*.swift（MediaScannerHandler / TagWriterHandler / AudioEffectsHandler），镜像 Android MainActivity 语义，改通道时两端要同步
- iOS 构建要求：部署目标 15.0+（Xcode 27）；Podfile post_install 统一抬升 Pods 部署目标
- 本机 Xcode 27 有 actool CAR 报错的环境坑，清理 DerivedData/Runner-* 可解
- 构建类命令在本机需绕过沙箱执行
