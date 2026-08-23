# Souti

<p align="center">
  <img src="assets/souti-icon.png" width="128" alt="Souti 图标">
</p>

Souti（搜题助手）是一款 Android 本地题库 OCR 检索工具，可导入自己的题库，通过浮窗、全屏读屏或摄像头扫描识别题目并显示匹配结果。

> 本仓库仅用于公开发布、使用说明和问题反馈，不包含应用源代码。

## 当前版本

- 最新公开版本：`v1.1.5`
- Android：8.0 及以上（API 26+）
- 支持架构：arm64-v8a / armeabi-v7a / x86_64
- 安装包：`Souti-v1.1.5-release.apk`

## 下载与校验`r`n`r`n正式 APK 和校验文件位于本仓库的 Releases 页面。

请从本仓库的 **Releases** 页面下载安装包，不要从不明来源获取 APK。

`v1.1.5` SHA-256：

```text
4128AAD7E058ED64E554C59AA1F1056FE945683E611C66F35567F516C0FE9FA9
```

Windows PowerShell 校验：

```powershell
Get-FileHash .\Souti-v1.1.5-release.apk -Algorithm SHA256
```

## 使用说明

### 1. 导入并选择题库

1. 打开首页“题库”，选择“智能导入”。
2. 选择 `.txt`、`.docx`、`.pdf` 或 `.xls` 文件；`.xlsx` 请先另存为 `.xls`。
3. 导入后进入题库总览，勾选参与匹配的题库。

### 2. 浮窗搜题

1. 点击“浮窗搜题”，按提示授权悬浮窗和录屏。
2. 拖动或缩放绿色识别框，使其覆盖需要识别的内容。
3. 结果显示在独立输出窗；标题栏用于拖动，内容区可上下滚动。

### 3. 读屏搜题

1. 点击“读屏搜题”，按提示授权悬浮窗和录屏。
2. 应用识别屏幕中的多道题目，并按顺序显示匹配结果。
3. 结果小窗可拖动、缩放和关闭。

### 4. 扫描搜题

1. 点击“扫描搜题”，授权摄像头。
2. 将内容置于绿色取景框内，可双指或使用按钮缩放。
3. 点击“暂停”锁定当前结果，点击“继续”恢复实时扫描。

## 隐私

OCR、截图、摄像头画面和题库匹配均在设备本地完成，应用不提供账号系统，也不上传用户题库。详情见 [PRIVACY_POLICY.md](PRIVACY_POLICY.md)。

## 问题反馈

请在本仓库的 [Issues](https://github.com/qingtianes/Souti/issues) 中提交问题。提交截图或题库样例前，请先删除姓名、账号、单位、试题原件和其他敏感信息。

## 版权与第三方组件

Souti 为专有软件，公开下载不代表开放源代码或授权再分发。第三方开源组件仍分别适用其原始许可证，详见 [LICENSE.md](LICENSE.md) 和 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。