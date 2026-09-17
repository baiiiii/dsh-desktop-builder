# dsh-desktop-builder

在 **GitHub Actions 上构建 DeepSeek Harness 的 Windows x64 桌面安装包**。

本仓库**不存放源码**——只保存一份 workflow 和一个补丁文件。源码在每次构建时从上游临时克隆，构建结束随 runner 销毁。

产物是未签名（unsigned）的，Windows 会弹出 SmartScreen 警告，需手动放行。

---

上游仓库：<https://github.com/deepseek-ai/deepseek-harness>
