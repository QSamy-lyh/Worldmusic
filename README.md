# Worldmusic
一个用 ArkTS + ArkUI 开发的鸿蒙系统（Harmony OS）简单本地音乐播放器，。本工程已针对 DevEco Studio 26 / HarmonyOS SDK 26.0.0（API 26） 配置（compatibleSdkVersion: "26.0.0"）
# 功能
- 基本音乐 播放 / 暂停 / 上一首 / 下一首（列表循环）
- 简单的播放功能，拥有沉浸的播放页面
- 使用系统 AVPlayer（@kit.MediaKit）做真实音频播放
# 运行方式（推荐直接导入本工程）
1. 安装 DevEco Studio 26（内置 HarmonyOS SDK 26.0.0，无需另装）。
2. 打开工程：File → Open，选择 MusicPlayer 文件夹（即包含 build-profile.json5 的根目录）。
3. 等待工程同步。如果顶部提示“工程同步失败”，先点 Try Again；若仍失败，按下方「同步失败排查」检查 SDK 版本。
4. 配置签名（真机/模拟器调试都需要）：File → Project Structure → Project → Signing Configs，勾选 Automatically generate signature。
5. 连接真机（开启开发者模式 + USB 调试）或启动模拟器，选择 Huawei Phone 后点击 Run（绿色三角）。
