<h1 align="center">SkyFetch</h1>

<p align="center">
  <a href="README.md">English</a> | <a href="README_zh.md">中文</a>
</p>

一个 Tampermonkey 脚本，可在含有图片的 BlueSky 帖子右下角添加下载按钮，自动下载最高分辨率版本，支持自定义命名规则。

支持多语言（英文、中文、日文、韩文、俄文）。

该项目的代码主要由 `OpenAI o1-mini`、`claude-3.5-sonnet` 和 `chatgpt-4o-latest` 编写，我提供了非常多的样式、功能设计提议和反馈。

本项目还使用了 [Twitter Media Downloader](https://greasyfork.org/zh-CN/scripts/423001-twitter-media-downloader) 项目的下载按钮 SVG，该项目基于 [MIT 许可证](https://opensource.org/licenses/MIT) 发布。

![使用示例](usage_example.png)

![下载结果](BlueSky_Bluesky_@bsky.app_2024-09-17_1_1o2i.jpg)
> BlueSky_Bluesky_@bsky.app_2024-09-17_1_1o2i.jpg

> BlueSky_用户名_ID_图片发布日期_图片序号_随机标识符.jpg

## 功能特性

- 在含图片的帖子右下角添加下载按钮
- 自动构造最高分辨率图像链接
- 自动下载图片的最高分辨率版本（BlueSky 平台限制为 .jpg 格式）
- 自动添加图像相关信息到文件名
- 可自定义文件命名规则
- 支持多语言（英文、中文、日文、韩文、俄文）
- 支持深色/浅色模式
- 本地数据处理，保护用户隐私
- 设置面板可自定义选项

## 安装方法

1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 访问 [SkyFetch 脚本](https://github.com/CookSleep/SkyFetch-Script/raw/main/SkyFetch-Script.user.js)
3. 在 Tampermonkey 中点击"安装"
> 对于使用基于 Chrome 浏览器的篡改猴扩展用户，启用开发者模式是根据 Manifest V3 更新引入的必要条件。您需要在浏览器的插件设置页面启用开发者模式，否则脚本将完全无法工作！

## 使用方法

1. 正常浏览 BlueSky
2. 看到含有图片的帖子时，点击右下角的下载按钮
3. 图片将自动以最高分辨率下载
4. 通过 Tampermonkey 菜单访问设置以自定义文件命名

## 贡献

欢迎对项目进行贡献！如果您有任何建议或想要添加新功能，请随时创建一个 Issue 或 Pull Request。

## 许可证

本项目采用 [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html) 许可证，详情请见 [LICENSE](LICENSE) 文件。