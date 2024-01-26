# 😎 awesome-trilium

<p align="center">
<a href="README.md">English</a> | 简体中文
</p>

> [!IMPORTANT]
> 中文文档可能落后于英文文档，如果有问题请先查看英文文档。

这是一个精选的 [Trilium Notes](https://github.com/zadam/trilium) 扩展列表，包括主题、小部件、脚本、API 扩展、ETAPI 等。

欢迎您在这里添加有关 Trilium Notes 的酷炫内容。

--------------------

## 🦮 目录

<!--ts-->

* [😎 awesome-trilium](#-awesome-trilium)
    * [🦮 目录](#-目录)
    * [📥 迁移到 Trilium](#-迁移到-trilium)
    * [🏡 主题](#-主题)
    * [✂️ CSS 片段](#-css-片段)
    * [⚙️ 小部件](#️-小部件)
    * [🪄 脚本](#-脚本)
    * [💥 扩展 HTML 笔记](#-扩展-html-笔记)
    * [📱 移动设备](#-移动设备)
        * [🤖 Android](#-android)
        * [🍎 iOS](#-ios)
    * [🧚 API 扩展](#-api-扩展)
    * [🖥️ ETAPI](#️-etapi)
        * [🦾 ETAPI 客户端](#-etapi-客户端)
        * [🤖 ETAPI 程序](#-etapi-程序)
    * [👨‍💻 开发工具](#-开发工具)
    * [🌐 翻译](#-翻译)
    * [🔥 贡献](#-贡献)

<!--te-->

## 📥 迁移到 Trilium

这些脚本和提示可用于从其他笔记应用迁移到 Trilium：

* [Evernote](https://github.com/zadam/trilium/wiki/Evernote-import)（Trilium Wiki 指南）Evernote 应用程序的最新版本不再包含将文件导出为
  enex 文件的选项。相反，它现在提供了一种不同的加密转储文件格式，其他人无法阅读。如果您想获得 enex
  文件，可能需要使用以下工具：https://github.com/vzhd1701/evernote-backup。
* [HTML](https://github.com/zadam/trilium/wiki/Markdown) 原生支持
* [Joplin](https://github.com/Nriver/trilium-py#import-from-joplin) 可以使用 trilium-py 导入。
* [Logseq](https://github.com/Nriver/trilium-py#import-from-logseq) 可以使用 trilium-py 导入。
* [Markdown](https://github.com/zadam/trilium/wiki/Markdown) 原生支持
* [Obsidian](https://github.com/Nriver/trilium-py#import-from-obsidian) 需要先将 Obsidian vault 转换为常规 Markdown
  文件，然后使用 trilium-py 导入以处理 Obsidian 的独特链接格式。在链接中了解更多信息。
* [OneNote](https://github.com/zadam/trilium/wiki/Onenote)（Trilium Wiki 指南）
* [Text](https://github.com/zadam/trilium/wiki/Markdown) 原生支持
* [Turtl](https://github.com/Nriver/trilium-py/tree/main/examples/turtl-to-markdown) 将 Turtl 笔记转换为 markdown 目录
* [Youdao Note/有道云笔记](https://github.com/Nriver/trilium-py#import-from-youdao-note%E6%9C%89%E9%81%93%E4%BA%91%E7%AC%94%E8%AE%B0)
  需要下载笔记并转换为 markdown。链接中提供更多详细信息。
* [VNote](https://github.com/Nriver/trilium-py#import-from-vnote) 可以使用 trilium-py 导入。将处理特殊的图像格式。
* [Zotero](https://github.com/paulusm/zotero-trilium) 一个 Zotero 插件，将笔记导出到 Trillium 笔记
* .OPML 内容可以原生读取和导入
* .TAR 内容可以原生读取和导入
* .ZIP 内容可以原生读取和导入

---

## 🏡 主题

**应用主题**

应用主题为 Trilium 应用提供主题。通常，这些笔记带有 `#appTheme` 标签，其中包含在 Trilium 选项面板中显示的主题名称。

* [Blue Theme](https://github.com/SiriusXT/trilium-theme-blue) 一个明亮而美丽的主题。感谢 SiriusXT！
* [breeze-trilium](https://github.com/eliandoran/breeze-trilium) 用于 Trilium Notes 的 KDE Breeze 主题
* [Catppuccin](https://github.com/SadAlexa/trilium-theme-catppuccin) 用 Catppuccin 调色板制作的 Trilium Notes 主题。
* [Chameleon Theme](https://github.com/DavidFuchs/trilium-chameleon-theme) 一组亮丽和深色色彩主题供 Trilium 使用。
* [Linen Theme](https://github.com/mondayrobot/trilium-linen-theme) 为 Trilium 设计的极简、通风的浅色主题，带有可选的无干扰模式。
* [Melon Theme](https://github.com/raphwriter/trilium-theme-melon) 一款令人愉悦的主题。
* [Mist-Moon](https://github.com/Ivy-End/Mist-Moon) 由 mist moon 夜景启发的浅色主题。
* [NieR-Automata Theme](https://github.com/Nriver/NieR-Automata-Trilium-Theme) 一个由我制作的，模仿 NieR-Automata 游戏 UI
  的主题 :)
* [Obsidian Theme](https://github.com/greengeek/trilium-obsidian-theme) Obsidian Note 主题。不是岩浆和水 :)
*
    * [Trilium Greensidian Theme](https://github.com/obuno/trilium-greensidian-theme) Obsidian 主题的绿色版本
* [Solarized theme](https://github.com/WKSu/trilium-solarized-theme) 将经典的 Solarized 主题带入 Trilium！有浅色和深色两个版本。
* [Stellar Dark Theme](https://github.com/Lolabird/stellar-dark-theme-trilium) 一种不同口味的深色主题。
* [VSCode-Dark Theme](https://github.com/greengeek/trilium-vscode-dark-theme) 它就是 VSCode！

**共享主题**

共享主题为共享笔记提供主题！共享笔记可以通过使用 `~shareCss` 关系到一个 css
笔记来使用自定义主题。有关更多信息，请参阅[为共享笔记设计样式](https://github.com/zadam/trilium/wiki/Sharing#styling-the-shared-notes)。

* [Ankia-Theme](https://github.com/dvai/Ankia-Theme) 一款卡片式 Trilium 博客主题。
* [FrostMiKu/Share.CSS](https://github.com/FrostMiKu/Share.CSS) 一个漂亮而清新的用于共享笔记的主题。你应该试试它！
* [ysslang's theme](https://github.com/zadam/trilium/discussions/2681) 带有阴影效果的纸张，很酷！

---

## ✂️ CSS 片段

自定义 CSS 用于改变 Trilium 的外观。这些代码片段通常带有 `#appCss` 标签。
请参阅 ([Trilium Wiki](https://github.com/zadam/trilium/wiki/Themes#custom-css)) 了解如何启用自定义 CSS 的说明。

* [将编辑的笔记显示为列表](https://github.com/zadam/trilium/discussions/2670#discussion-3884786)
* [从目录中删除数字](https://github.com/zadam/trilium/discussions/3873#discussioncomment-5710601)
* [树形结构的垂直线](https://github.com/zadam/trilium/issues/3892#issuecomment-1530144842)
* [改进活动日历天数的可见性](https://github.com/Nriver/awesome-trilium/issues/30)

---

## ⚙️ 小部件

小部件可以在 Trilium 用户体验中产生重大影响！

小部件通常改变 Trilium 的用户界面，并提供额外的面板功能。小部件的主 JavaScript 文件通常带有 `#widget`。

* [Breadcrumbs](https://github.com/rauenzi/Trilium-Breadcrumbs) 在页面底部显示笔记面包屑导航
* [command-palette](https://github.com/justyns/trilium-scripts) Trilium 的简单命令面板
* [hexmap](https://gitlab.com/QuentinLeCaignec/trilium-hexmap) 交互式 hexmap（适用于 TTRPGs）
* [openfilepath](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) 双击时打开斜体文件路径
* [Scratchpad](https://github.com/zadam/trilium/discussions/1613#discussioncomment-638984) 为笔记添加便签小部件
* [Syntax Highlight](https://github.com/antoniotejada/Trilium-SyntaxHighlightWidget) 你想要的语法高亮功能
* [Theme Switch](https://github.com/madodig/trilium-widget-theme-switch) 用于切换主题的 Trilium 小部件
* [timeline](https://gitlab.com/QuentinLeCaignec/trilium-timeline) 交互式时间线
* [tomato-timer](https://github.com/Nriver/tomato-timer-widget) 用于 Trilium Notes 的番茄钟计时器
* [trilium-auto-hide-info-bar](https://github.com/SiriusXT/trilium-auto-hide-info-bar) 自动隐藏标题栏和信息栏，并且您可以单独设置其中一个隐藏。
* [trilium-back-to-history](https://github.com/SiriusXT/trilium-back-to-history) 跳转到上次浏览的位置
* [trilium-left-panel-auto-zoom](https://github.com/SiriusXT/trilium-left-panel-auto-zoom)
  通过移动鼠标自动扩展笔记树。这是一个方便的小部件，用于浏览具有长标题和深层级笔记的场景。
* [trilium-remember-right-pane](https://github.com/SiriusXT/trilium-remember-right-pane)
  允许您点击一个按钮在关闭右侧目录窗口后再次打开它。通过标签记住右侧窗口的状态。
* [trilium-show-position-in-toc](https://github.com/SiriusXT/trilium-show-position-in-toc) 在目录中标记正在浏览的位置的字体为红色。
* [Trilium-TocWidget](https://github.com/Lolabird/Trilium-TocWidget) 目录小部件现在是 Trilium Notes
  的内置功能。非常感谢开发者 [antoniotejada](https://github.com/antoniotejada/Trilium-TocWidget)
  和 [Lolabird](https://github.com/Lolabird/Trilium-TocWidget)！

## 🪄 脚本

神奇！这些代码笔记通常在 Trilium 中标记为 JS 前端。它们通常带有 `#run=frontendStartup` 标签，以便在 Trilium
启动时自动执行。请记住，脚本是可执行代码，谨慎处理！

* [Better Include](https://github.com/salmund/trilium_better_include) 使子笔记的包含更快
* [Calendar & Timetable](https://github.com/Mangiola/trilium-scripts) 实现日历、时间表，甚至包括音乐琴颈。
* [Dark-mode-img-color-conversion](https://github.com/zadam/trilium/discussions/4209) 调整网页上的图像和背景颜色以适应暗黑主题。
* [Font formatting shortcuts](https://github.com/zadam/trilium/issues/2954#issuecomment-1672431589) 文本格式的自定义快捷键，用于
  CKEditor 中的文本格式设置，极大提升编辑效率。
* [gistMirror](https://github.com/jwhonce/trilium-addons/blob/main/gistMirror/gistMirror.js) 镜像 GitHub Gists 到
  Trilium 笔记树
* [Mobile View](https://github.com/BeatLink/trilium-scripts/tree/main/Mobile%20View) 这组脚本允许您在移动设备上充分利用
  Trilium 服务器用户界面的全部功能。
* [Open note in split view](https://github.com/zadam/trilium/discussions/3937) Shift+点击以在分割视图中打开一个笔记。Ctrl+Shift+点击树节点。
* [OpenFilePaths](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) 双击可以打开斜体文件或文件夹路径。
* [Startup message](https://github.com/Nriver/trilium-translation/blob/main/demo-cn/示例笔记%20-%20请不要删除/Trilium%20扩展/Trilium%20脚本%20script/startup%20启动项/startup%20message%20启动信息.js)
  一个非常简单的脚本。显示一条随机消息。设置 `#run=frontendStartup` 以在 Trilium 启动时运行。就像 MOTD（每日消息）一样 :)
* [Trillium Agenda](https://github.com/BeatLink/trilium-agenda) 将待办事项分类为6个类别：过期、今天、本周、本月、今年、未来
* [Trilium-chat](https://github.com/soulsands/trilium-chat) Trilium 的聊天插件目前支持 ChatGPT

---

## 💥 扩展 HTML 笔记

增强的 HTML 显示笔记通常包含复杂的功能，并通常使用 `~renderNote` 关系呈现复杂的独立 HTML 页面，超越小面板的功能。

* [drawio](https://github.com/SiriusXT/trilium-drawio) 集成的 drawio 插件
* [LaTeXPreview](https://github.com/rauenzi/Trilium-LaTeXPreview) Trilium Notes 的 LaTeX 预览小部件
* [MarkdownPreview](https://github.com/rauenzi/Trilium-MarkdownPreview/) 实时预览支持锚点、图像和同步滚动的 Markdown 文件
* [trilium-collection-views](https://github.com/mabeyj/trilium-collection-views) 用于以不同方式显示笔记的优秀扩展。
* [Trilium-Heatmap](https://github.com/dvai/Trilium-Heatmap) 在 Trilium 笔记中显示修改热力图
* [Trilium JSON Editor](https://github.com/sottey/tje) Trilium 的 JSON 笔记编辑器
* [Trilium-SingleFile](https://github.com/rauenzi/Trilium-SingleFile) 用于轻松导入 SingleFile 存档的 Trilium 插件。
* [Kanban View](https://github.com/CyrilLeblanc/trilium-kanban) Trilium Notes 的看板集成

---

## 📱 移动端

与手机相关的酷炫功能。

### 🤖 Android

* [在 Android 的 Termux 上运行 Trilium 服务器](https://github.com/zadam/trilium/discussions/4542)
  服务器随身携带。玩得开心 :)
* [trilium-sender](https://github.com/zadam/trilium-sender) 一个简单的只写 Android 应用，用于将图像和笔记发送到 Trilium。

### 🍎 iOS

* [trilium-ios-shortcut](https://github.com/soulsands/trilium-ios-shortcut) 通过 Apple 快捷方式发送消息到 Trilium 的教程。

---

## 🧚 API 扩展

更多的魔法！

注意！此类别中的插件涉及自定义请求处理程序（用户定义的 API）。请谨慎使用！

* [singlefile2trilium](https://github.com/nil0x42/singlefile2trilium)
  利用 [SingleFile](https://github.com/gildas-lormeau/SingleFile) 网页扩展的强大功能，您可以在 Trilium 中获得网页的完美副本。

---

## 🖥️ ETAPI

Trilium 的外部 API（也称为 [ETAPI](https://github.com/zadam/trilium/wiki/ETAPI)）相关的内容。

### 🦾 ETAPI 客户端

ETAPI 的客户端实现。

* [trilium-py](https://github.com/Nriver/trilium-py) Trilium Note 的 ETAPI 的 Python 客户端，带有一些额外的酷炫功能。
* [pytrilium](https://github.com/perfectra1n/pytrilium) Trilium Notes 的 ETAPI 的 Python 客户端，包含所有当前有效的 ETAPI
  路径，并实现了一个自定义的底层 `requests` 会话。
* [trilium-alchemy](https://github.com/mm21/trilium-alchemy) Trilium Notes 的 Python SDK 和 CLI 工具包。
* [trilium-etapi](https://github.com/rauenzi/trilium-etapi) 围绕 Trilium Notes 的 ETAPI 的 Node.js 封装。

### 🤖 ETAPI 程序

基于 Trilium ETAPI 的程序。

* [trilium-bot](https://github.com/Nriver/trilium-bot) 用于 Trilium
  的演示电报机器人，由 [trilium-py](https://github.com/Nriver/trilium-py) 驱动。

---

## 👨‍💻 开发工具

用于开发 Trilium 及其插件的开发工具。

* [trilium-pack](https://github.com/rauenzi/trilium-pack) 用于将插件打包为 Trilium Notes 的 `zip` 文件的简便方法。
* [trilium-types](https://github.com/rauenzi/trilium-types) 用于 Trilium Notes 的 TypeScript `@types` 包。

---

## 🌐 翻译

Trilium Notes 的第三方翻译。

* [trilium-translation](https://github.com/Nriver/trilium-translation) Trilium 的非官方翻译项目。目前已完成中文翻译。

## 🔥 贡献

欢迎 fork 并贡献到这个仓库。

[目录](#table-of-contents)
部分由 [https://github.com/ekalinin/github-markdown-toc](https://github.com/ekalinin/github-markdown-toc) 生成。然后在
PyCharm 中通过 `Ctrl + Alt + L` 进行重新格式化。
