# 霁序 JISEQ · 安装包发布

这是 A 股量化研究与模拟盘桌面终端「霁序 JISEQ」的**安装包发布仓库**：只存放 macOS 安装包（Releases），不含源码。

- 下载：见右侧 [Releases](https://github.com/ouyangCL/jiseq-releases/releases)
- 应用内置在线更新会检查本仓库的最新 Release，下载 DMG 并校验 sha256 后提示安装
- 源码不公开；安装包含应用的可执行字节码

## 安装

1. 从 Releases 下载 `JISEQ-<版本>-macOS-arm64.dmg`，拖入「应用程序」；或使用 `.pkg` 安装器。
2. 需要 Apple Silicon 与 macOS 14+，无需安装 Python。
3. 安装包为 ad-hoc 签名（未公证）：首次打开若被 Gatekeeper 拦截，右键应用选「打开」一次即可。
