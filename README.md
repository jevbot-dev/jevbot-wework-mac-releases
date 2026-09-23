# Jevbot · 企业微信（macOS）

企业微信聊天副驾：读到对方最新消息，判断真实意图和风险，给出 3 条候选回复，一键填入输入框。

**发送永远由你自己按**：Jevbot 只填入，不自动发送，不碰转账红包收款。

这个仓库只放安装包，只带企业微信一个应用的支持。想同时支持多个应用，下载
[完整版](https://github.com/jevbot-dev/jevbot-mac-releases/releases/latest)。

## 下载

[最新版本](https://github.com/jevbot-dev/jevbot-wework-mac-releases/releases/latest) · 系统要求 macOS 14 及以上 · 已用 Developer ID 签名并经 Apple 公证

## 安装

1. 下载 `Jevbot-wework-<版本>.dmg`，打开后把 Jevbot 拖进「应用程序」
2. 在 **系统设置 › 隐私与安全性** 里勾上 Jevbot 的
   - **辅助功能**（读取聊天内容、填入输入框）
3. 授权后**退出并重新打开** Jevbot（macOS 不会给已在运行的程序补发权限）
4. 菜单栏 Jevbot → 设置 → 接口，填 TypeSafe（判断）和 DeepSeek（回复）的密钥，点「测试连接」

每个版本附带 `SHA256SUMS.txt`，下载后可以校验：

```bash
shasum -a 256 -c SHA256SUMS.txt
```

## 隐私

密钥只进登录钥匙串，不落配置文件、不进日志。不注入、不 hook、不改企业微信，不读它的数据库。

## 反馈

问题和适配需求提到 [jevbot-mac-releases Issues](https://github.com/jevbot-dev/jevbot-mac-releases/issues)。
微信群、社交账号见 [jevbot-mac-releases](https://github.com/jevbot-dev/jevbot-mac-releases#微信)。
