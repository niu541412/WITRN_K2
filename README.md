# WITRN K2 网页刷机工具

通过 Chrome 或 Edge 的 WebHID 功能给 WITRN K2 刷写固件。网页为单文件，无需安装软件。

**在线使用：** https://niu541412.github.io/WITRN_K2_flash/

## 使用方法

1. 将 K2 进入 DFU 模式并连接电脑。
2. 在 Chrome 或 Edge 打开在线页面，点击“连接 K2 (DFU)”并授权设备。
3. 从本机选择 `.k2` 固件文件，确认校验通过后再开始刷机。固件文件无需上传到 GitHub。

## 来源

本工具基于 [kuaner 的原始 Gist](https://gist.github.com/kuaner/46140db4f1f373b26b32c485ef125c73)。本仓库调整了后台标签页的逐包等待方式，避免定时器限速导致刷机进度停滞。
