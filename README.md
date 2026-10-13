# PDD Assistant 官方发布

这里仅发布经过混淆和打包的安装文件，不包含开发源码。

- Windows x64：运行版本对应的 `Setup.exe`，然后在 `chrome://extensions/` 或 `edge://extensions/` 开启开发者模式并加载安装目录中的 `extension` 文件夹。
- macOS（Apple Silicon / Intel）：解压 ZIP，运行 `install.command`，然后在 Chrome 或 Edge 的扩展管理页加载 `~/Library/Application Support/PddAssistant/extension`。
- 打开拼多多商家页面内的“授权管理”，输入管理员发放的 `OL1-` 授权码。已有旧版 `.pddlicense` 可继续使用至原到期日。

[查看版本与下载](https://github.com/orange-pix-web/PDD-Assistant-Releases/releases)

## 安全提示

请核对发布页给出的 SHA-256。安装包目前未做 Apple/Windows 代码签名；首次运行可能显示系统来源提示。
