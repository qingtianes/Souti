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
| JExcelAPI (jxl) 2.6.12 | `.xls` 文件解析 | GNU Lesser General Public License (LGPL) |
| Log4j 1.2.14 | JExcelAPI 传递依赖 | Apache License 2.0 |

## 许可证文本

Apache License 2.0：
https://www.apache.org/licenses/LICENSE-2.0

GNU LGPL：
https://www.gnu.org/licenses/lgpl-2.1.html

Bouncy Castle License：
https://www.bouncycastle.org/licence.html

Google ML Kit 条款：
https://developers.google.com/terms

## JExcelAPI 说明

JExcelAPI 以 LGPL 发布。Souti 未修改其上游源代码，并通过独立依赖形式使用。用户可从其上游项目或 Maven Central 获取对应版本的源代码和许可证文本。

本文件不是法律意见。如需商业分发或在特定司法辖区发布，应另行进行许可证合规审查。