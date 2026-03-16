# 使用Github Pages的DOCX转Markdown转换器

TODO: 使用 <https://github.com/microsoft/markitdown> 进行更新
这是一个静态托管网站，允许用户上传 `.docx` 文件并将其转换为Markdown (`.md`)。该网站使用JavaScript库Mammoth.js和Turndown.js在浏览器中直接执行转换。

### - <https://michaelakridge-noaa.github.io/docx-to-md-web/>

## 功能

- **上传和转换**：用户可以上传 `.docx` 文件，然后将其转换为Markdown。
- **下载Markdown**：转换后，用户可以单击一下下载Markdown文件。

[!\[\](./docs/s01.png null)](https://michaelakridge-noaa.github.io/docx-to-markdown-web)

## 工作原理

1. **上传DOCX文件**：点击"选择文件"按钮从您的计算机中选择一个 `.docx` 文件。
2. **转换**：使用Mammoth.js（用于DOCX到HTML）和Turndown.js（用于HTML到Markdown）将文件转换为Markdown。
3. **下载**：转换完成后，会出现"下载Markdown"按钮。点击它将转换后的文件下载为 `converted.md`。

## 使用方法

此网站托管在GitHub Pages上。只需访问该网站，上传您的 `.docx` 文件，然后下载Markdown版本。

## credits / 使用的库

- [Architect Jekyll Theme](https://github.com/pages-themes/architect)：用于GitHub Pages
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js)：将 `.docx` 文件转换为HTML。
- [Turndown.js](https://github.com/domchristie/turndown)：将HTML转换为Markdown。

***

### 免责声明

本存储库是一个科学产品，不是美国国家海洋和大气管理局或美国商务部的官方通信。所有NOAA GitHub项目内容均按"原样"提供，用户对其使用承担责任。因使用本GitHub项目而对商务部或商务部局提出的任何索赔将受所有适用的联邦法律管辖。任何通过服务标记、商标、制造商或其他方式对特定商业产品、流程或服务的引用，均不构成或暗示商务部对其的认可、推荐或支持。商务部的印章和标志，或DOC局的印章和标志，不得以任何方式用于暗示DOC或美国政府对任何商业产品或活动的认可。

#### 许可证

有关详细信息，请参阅 [LICENSE.md](./LICENSE.md)
