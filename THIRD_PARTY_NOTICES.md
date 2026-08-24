# 第三方开源组件声明

Souti 是专有软件，但包含第三方开源组件。以下清单用于履行版权和许可证告知义务；各组件仍适用其原始许可证。

## 主要组件

| 组件 | 用途 | 许可证 |
|---|---|---|
| AndroidX / Jetpack Compose / CameraX | Android UI、生命周期和摄像头 | Apache License 2.0 |
| Kotlin 标准库及协程相关组件 | Kotlin 运行时 | Apache License 2.0 |
| Google ML Kit Text Recognition | 本地 OCR | Google 相关条款及随组件提供的第三方声明 |
| PdfBox-Android 2.0.27.0 | PDF 文字与图片解析 | Apache License 2.0 |
| Bouncy Castle 1.72 | PdfBox-Android 传递依赖 | Bouncy Castle License |
| Apache POI（Android 适配版 poi-android 3.17，基于 Apache POI 3.17） | `.xls` 文件解析 | Apache License 2.0 |


## 许可证文本

Apache License 2.0：
https://www.apache.org/licenses/LICENSE-2.0

Bouncy Castle License：
https://www.bouncycastle.org/licence.html

Google ML Kit 条款：
https://developers.google.com/terms

## Apache POI 说明

Souti 使用 Apache POI 的 Android 适配版 poi-android（3.17，基于 Apache POI 3.17）读取旧式 `.xls` 文件，未修改其上游源代码。Apache POI 及其适用传递依赖按 Apache License 2.0 或各自原始许可证分发。
