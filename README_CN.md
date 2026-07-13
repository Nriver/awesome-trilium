# 😎 awesome-trilium

<p align="center">
<a href="README.md">English</a> | 简体中文
</p>

> [!IMPORTANT]
> 中文文档可能落后于英文文档，如果有问题请先查看英文文档。中文文档通过GPT翻译，可能会有不准确的地方，有条件的还请阅读英文版文档。

这是一个精选的 [Trilium Notes](https://github.com/zadam/trilium) 扩展列表，包括主题、小部件、脚本、API 扩展、ETAPI 等。

欢迎您在这里添加有关 Trilium Notes 的酷炫内容。

--------------------

## 🦮 目录

<!--ts-->
* [😎 awesome-trilium](#-awesome-trilium)
   * [🦮 目录](#-目录)
   * [📥 迁移到 Trilium](#-迁移到-trilium)
   * [🏡 主题](#-主题)
   * [🎨 图标包](#-图标包)
      * [官方图标包](#官方图标包)
      * [第三方图标包](#第三方图标包)
   * [✂️ CSS 片段](#️-css-片段)
   * [⚙️ 小部件](#️-小部件)
   * [🪄 脚本](#-脚本)
   * [💥 扩展 HTML 笔记](#-扩展-html-笔记)
   * [📱 移动端](#-移动端)
      * [🤖 Android](#-android)
      * [🍎 iOS](#-ios)
   * [🧚 API 扩展](#-api-扩展)
   * [🖥️ ETAPI](#️-etapi)
      * [🦾 ETAPI 客户端](#-etapi-客户端)
      * [🤖 ETAPI 程序](#-etapi-程序)
   * [🧩 Chrome 扩展程序](#-chrome-扩展程序)
   * [👨‍💻 开发工具](#-开发工具)
   * [📚 维基和文档](#-维基和文档)
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

* [Allure 主题](https://github.com/JadeVane/Allure) ![Allure](https://img.shields.io/github/last-commit/Nriver/bing-daily-theme)  
  一个更美丽和简洁的 Trilium 主题。
  
* [必应每日主题](https://github.com/Nriver/bing-daily-theme) ![必应每日主题](https://img.shields.io/github/last-commit/Nriver/bing-daily-theme)  
  每天自动换为必应每日壁纸。
  
* [蓝色主题](https://github.com/SiriusXT/trilium-theme-blue) ![蓝色主题](https://img.shields.io/github/last-commit/SiriusXT/trilium-theme-blue)
  一个明亮而美丽的主题。感谢SiriusXT！
  
* [breeze-trilium](https://github.com/eliandoran/breeze-trilium) ![breeze-trilium](https://img.shields.io/github/last-commit/eliandoran/breeze-trilium)
  适用于 Trilium Notes 的 KDE Breeze 主题
  
* [Catppuccin](https://github.com/SadAlexa/trilium-theme-catppuccin) ![Catppuccin](https://img.shields.io/github/last-commit/SadAlexa/trilium-theme-catppuccin)
  适用于 Trilium Notes 的主题，使用 Catppuccin 调色板制作。
  
* [Chameleon 主题](https://github.com/DavidFuchs/trilium-chameleon-theme) ![Chameleon 主题](https://img.shields.io/github/last-commit/DavidFuchs/trilium-chameleon-theme)
  Trilium 的浅色和深色主题套装。
  
* [eva theme](https://github.com/cocolight/trilium-theme-eva) ![eva Theme](https://img.shields.io/github/last-commit/cocolight/trilium-theme-eva)
 一个将 Eva 主题插件的风格带到 VSCode 的主题，包括 eva-light、eva-dark 和 eva-night。

* [EverForest Ant Dark (EFAD) Trilium 主题](https://github.com/Lolabird/everforest-ant-dark-trilium-theme) ![EverForest Ant Dark (EFAD) Trilium 主题](https://img.shields.io/github/last-commit/Lolabird/everforest-ant-dark-trilium-theme)  
  Trilium Notes 主题与 Everforest 和 Ant Dark Linux 桌面主题相配。
  
* [Lightpad](https://github.com/ohmstance/trilium-lightpad-theme) ![Lightpad](https://img.shields.io/github/last-commit/ohmstance/trilium-lightpad-theme)  一款明亮的主题，具有许多用户友好的调整，极大地增强了移动端的体验。

* [亚麻主题](https://github.com/mondayrobot/trilium-linen-theme) ![亚麻主题](https://img.shields.io/github/last-commit/mondayrobot/trilium-linen-theme)
  适用于 Trilium 的极简、通风的亮色主题，带有可选的无干扰模式。
  
* [甜瓜主题](https://github.com/raphwriter/trilium-theme-melon) ![甜瓜主题](https://img.shields.io/github/last-commit/raphwriter/trilium-theme-melon)
  一款令人愉悦的主题。
  
* [柠檬树](https://github.com/yu-jingrui/trilium-theme-lemon-tree) ![柠檬树](https://img.shields.io/github/last-commit/yu-jingrui/trilium-theme-lemon-tree)
  一款令人愉悦的主题。基于TriliumNext浅色主题，受到甜瓜主题的启发。
  
* [薄雾月夜](https://github.com/Ivy-End/Mist-Moon) ![薄雾月夜](https://img.shields.io/github/last-commit/Ivy-End/Mist-Moon)
  一款受薄雾月夜景象启发的浅色主题。
  
* [尼尔：自动人形主题](https://github.com/Nriver/NieR-Automata-Trilium-Theme) ![尼尔：自动人形主题](https://img.shields.io/github/last-commit/Nriver/NieR-Automata-Trilium-Theme)
  由粉丝制作的尼尔：自动人形游戏用户界面风格主题。这个主题是我制作的 :)
  
* [Obsidian 主题](https://github.com/greengeek/trilium-obsidian-theme) ![Obsidian 主题](https://img.shields.io/github/last-commit/greengeek/trilium-obsidian-theme)
    深色主题，并带有少量紫色点缀
    * [Trilium Greensidian 主题](https://github.com/obuno/trilium-greensidian-theme) ![Trilium Greensidian 主题](https://img.shields.io/github/last-commit/obuno/trilium-greensidian-theme)
      Obsidian 主题的绿色版本
    
* [Solarized 主题](https://github.com/WKSu/trilium-solarized-theme) ![Solarized 主题](https://img.shields.io/github/last-commit/WKSu/trilium-solarized-theme)
  将经典的 Solarized 主题带到 Trilium 中！提供浅色和深色两种版本。
  
* [星际黑暗主题](https://github.com/Lolabird/stellar-dark-theme-trilium) ![星际黑暗主题](https://img.shields.io/github/last-commit/Lolabird/stellar-dark-theme-trilium)
  一款不同风格的深色主题。
  
* [VSCode-Dark 主题](https://github.com/greengeek/trilium-vscode-dark-theme) ![VSCode-Dark 主题](https://img.shields.io/github/last-commit/greengeek/trilium-vscode-dark-theme)
  它就是 VSCode！
  
* [Ra1n 的深色主题](https://github.com/perfectra1n/custom-trilium-themes) ![Ra1n's Dark Theme](https://img.shields.io/github/last-commit/perfectra1n/custom-trilium-themes)
  一款深色主题，外观漂亮且对眼睛友好！


**分享主题**

分享主题为分享笔记提供主题！分享笔记可以通过使用 `~shareCss` 关系到一个 css
笔记来使用自定义主题。有关更多信息，请参阅[为分享笔记设计样式](https://github.com/zadam/trilium/wiki/Sharing#styling-the-shared-notes)。

* [Ankia 主题](https://github.com/dvai/Ankia-Theme) ![Ankia 主题](https://img.shields.io/github/last-commit/dvai/Ankia-Theme)
  一款以卡片风格设计的 Trilium 博客主题。
* [FrostMiKu/Share.CSS](https://github.com/FrostMiKu/Share.CSS) ![FrostMiKu/Share.CSS](https://img.shields.io/github/last-commit/FrostMiKu/Share.CSS)
  一款漂亮而清新的主题，专为分享笔记而设计。你值得一试！
* [uweizh/trilium-sharecss](https://github.com/uweizh/trilium-sharecss) ![uweizh/trilium-sharecss](https://img.shields.io/github/last-commit/uweizh/trilium-sharecss)
  一款渐变色的分享主题。
* [WhiteMinimalist-Theme](https://github.com/Shmaur/WhiteMinimalist-Theme) ![WhiteMinimalist-Theme](https://img.shields.io/github/last-commit/Shmaur/WhiteMinimalist-Theme)
  一个白色极简风格的博客主题。
* [ysslang's 主题](https://github.com/zadam/trilium/discussions/2681) ![ysslang's 主题](https://img.shields.io/github/gist/last-commit/46e2a57ca95ba9c7368cbd255d1ac769)
  纸张效果搭配阴影效果，酷毙了！
* [trilium.rocks 主题](https://github.com/perfectra1n/trilium.rocks/releases/tag/1.0.0) ![trilium.rocks theme](https://img.shields.io/github/last-commit/perfectra1n/trilium.rocks)  
  此主题与 [trilium.rocks](https://trilium.rocks/) 网站（@zerebos 开发）上使用的主题相同。上面的链接还包括安装说明。你也可以通过 [此处](https://trilium.rocks/xecUJ8eL3pvM) 从头创建。
* [Akari 主题](https://github.com/march-7th-mini/Trilium-X-Akari) ![Akari 主题](https://img.shields.io/github/last-commit/march-7th-mini/Trilium-X-Akari)
  基于Ankia、WhiteMinimalist主题进行修改。美化了首页、内嵌了kimi chat、增加了蒙版颜色设置、增加了折叠无序List、增加了代码块折叠、增加了目录搜索与折叠展开、增加了石蒜小组件、增加了背景音乐、增加了导航全展开菜单、汉化了mathjax的右键菜单、增加了评论表情悬停放大预览、扩展了可设置背景图片的页面、修复了一些bug等等。
* [zfy 主题](https://github.com/brucevon/zfy) ![zfy 主题](https://img.shields.io/github/last-commit/brucevon/zfy)
  一个简单卡片风格的 Trilium 博客主题。
---

## 🎨 图标包

**图标包**功能自 Trilium 0.102.0 版本起引入。通过图标包，自定义您的笔记外观。

### 官方图标包

点击查看[官方 Trilium 图标包](https://triliumnotes.org/resources/)。

### 第三方图标包

* [hulmgulm/trilium-icons](https://github.com/hulmgulm/trilium-icons) ![hulmgulm/trilium-icons](https://img.shields.io/github/last-commit/hulmgulm/trilium-icons)
  包含多个图标包：

  * Emoji 图标包：此图标包允许将大多数表情符号字符用作笔记图标。
  * Font-Awesome 图标包：使用大多数免费的 Font-Awesome 图标作为笔记图标。
  * Material Design 图标包：使用 Google Material Design 图标作为笔记图标。

---

## ✂️ CSS 片段

自定义 CSS 用于改变 Trilium 的外观。这些代码片段通常带有 `#appCss` 标签。
请参阅 ([Trilium Wiki](https://github.com/zadam/trilium/wiki/Themes#custom-css)) 了解如何启用自定义 CSS 的说明。

* [活动日历天可见性改进](https://github.com/Nriver/awesome-trilium/issues/30)
* [将编辑后的笔记显示为列表](https://github.com/zadam/trilium/discussions/2670#discussion-3884786)
* [水平滚动条](https://github.com/zadam/trilium/discussions/4706) 一个 CSS 片段，用于使左侧面板和目录显示水平滚动条。
* [带透明背景的图像](https://github.com/TriliumNext/Notes/issues/361) 为透明图像添加透明背景。
* [从目录中删除编号](https://github.com/zadam/trilium/discussions/3873#discussioncomment-5710601)
* [trilium-enhancement](https://github.com/Nriver/trilium-enhancement) ![trilium-enhancement](https://img.shields.io/github/last-commit/Nriver/trilium-enhancement) Trilium Notes 的体验增强工具包。
* [Trilium-TextNoteEnhancement](https://github.com/SiriusXT/Trilium-TextNoteEnhancement) ![Trilium-TextNoteEnhancement](https://img.shields.io/github/last-commit/SiriusXT/Trilium-TextNoteEnhancement)  
  提供了一些小部件，用于提升 Trilium 文本输入效率。
* [树形结构垂直线](https://github.com/zadam/trilium/issues/3892#issuecomment-1530144842)
* [禅模式](https://github.com/Nriver/awesome-trilium/issues/44) 将禅模式添加到您的 Trilium 中。
* [trilium-enhancement-Lazy-Pack](https://github.com/march-7th-mini/trilium-enhancement-Lazy-Pack) ![trilium-enhancement-Lazy-Pack](https://img.shields.io/github/last-commit/march-7th-mini/trilium-enhancement-Lazy-Pack)
  Trilium Notes V0.63.7的体验增强精选懒人工具包。包括一个VOCALOID歌姬应援色主题、「只读模式」生效的图片缩放、拖动和预览、使用iframe内嵌的方式接入kimi-chat等21个增强扩展。

---

## ⚙️ 小部件

小部件可以在 Trilium 用户体验中产生重大影响！

小部件通常改变 Trilium 的用户界面，并提供额外的面板功能。小部件的主 JavaScript 文件通常带有 `#widget`。

* [AI Voice Note Widget](https://github.com/Userwei0418/trilium_AI_Voice_Note-) ![AI Voice Note Widget](https://img.shields.io/github/last-commit/Userwei0418/trilium_AI_Voice_Note-)
  一个用于 Trilium Notes 的全功能语音转写与智能整理小组件。
* [Breadcrumbs](https://github.com/rauenzi/Trilium-Breadcrumbs) ![Breadcrumbs](https://img.shields.io/github/last-commit/rauenzi/Trilium-Breadcrumbs)
  在页面底部显示笔记的面包屑导航
* [命令面板](https://github.com/justyns/trilium-scripts) ![命令面板](https://img.shields.io/github/last-commit/justyns/trilium-scripts)
  Trilium 的简易命令面板
* [在笔记中转换公式](https://github.com/zadam/trilium/discussions/4792)
  将用单个美元符号 `$` 和双美元符号 `$$` 包裹的数学公式转换为 Trilium Notes 中的 HTML 格式。
* [复制代码块](https://github.com/Nriver/copy-code-block-widget) ![命令面板](https://img.shields.io/github/last-commit/Nriver/copy-code-block-widget)
  双击以复制代码块
* [倒计时天数](https://github.com/Nriver/countdown-days-widget) ![倒计时天数](https://img.shields.io/github/last-commit/Nriver/countdown-days-widget)
  在日记标题下添加相对天数信息。
* [hexmap](https://gitlab.com/QuentinLeCaignec/trilium-hexmap) ![hexmap](https://img.shields.io/gitlab/last-commit/QuentinLeCaignec/trilium-hexmap)
  交互式 hexmap（适用于 TTRPGs）
* [MusicPlayer](https://github.com/Userwei0418/trilium-MusicPlayer) ![MusicPlayer](https://img.shields.io/gitlab/last-commit/Userwei0418/trilium-MusicPlayer)
  在trilium使用脚本实现一个简单的音乐播放器 支持播放暂停、调节音量、调整播放顺序、隐藏与显示
* [Image zoom](https://github.com/Nriver/image-zoom-widget) ![Image zoom](https://img.shields.io/github/last-commit/Nriver/image-zoom-widget)
  在 Trilium 中缩放、拖动和预览图片
* [Knowledge Card Gallery](https://github.com/Userwei0418/trilium_Knowledge-Gallery-Viewer) ![Knowledge Card Gallery](https://img.shields.io/github/last-commit/Userwei0418/trilium_Knowledge-Gallery-Viewer)
  为 Trilium Notes 设计的沉浸式知识内化工具。它能将枯燥的笔记文本转化为可视化的「知识卡片」和「翻转复习卡」，并集成了 AI 智能提取功能，帮助你快速整理核心观点、进行间隔重复复习。
* [Magic Toolbox](https://github.com/Userwei0418/trilium-Magic-Toolbox) ![Magic Toolbox](https://img.shields.io/github/last-commit/Userwei0418/trilium-Magic-Toolbox)
  将你的 Trilium 变成一个轻量级操作系统，让脚本像“小程序”一样运行。
* [openfilepath](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) ![openfilepath](https://img.shields.io/github/gist/last-commit/de1f386fac9f9e797fd77022d63967c9)
  双击打开斜体显示的文件路径
* [Scratchpad](https://github.com/zadam/trilium/discussions/1613#discussioncomment-638984)
  在笔记中添加草稿板小部件
* [语法高亮](https://github.com/antoniotejada/Trilium-SyntaxHighlightWidget) ![语法高亮](https://img.shields.io/github/last-commit/antoniotejada/Trilium-SyntaxHighlightWidget)
  你所期望的语法高亮功能。
* [交换 enter](https://github.com/Nriver/swap-enter-widget) ![Swap enter](https://img.shields.io/github/last-commit/Nriver/swap-enter-widget)
  交换Trilium Notes 的 "enter" 和 "shift + enter".
* [标题颜色选择器](https://github.com/Nriver/swap-enter-widget) ![标题颜色选择器](https://img.shields.io/github/last-commit/Nriver/swap-enter-widget)
  一个美观且直观的标题颜色选择器小组件，适用于 Trilium Notes
* [主题切换](https://github.com/madodig/trilium-widget-theme-switch) ![主题切换](https://img.shields.io/github/last-commit/madodig/trilium-widget-theme-switch)
  用于更改主题的 Trilium 小部件
* [时间轴](https://gitlab.com/QuentinLeCaignec/trilium-timeline) ![时间轴](https://img.shields.io/gitlab/last-commit/QuentinLeCaignec/trilium-timeline)
  交互式时间轴
* [番茄计时器](https://github.com/Nriver/tomato-timer-widget) ![番茄计时器](https://img.shields.io/github/last-commit/Nriver/tomato-timer-widget)
  Trilium Notes 的番茄计时器
  * [番茄计时器](https://github.com/Userwei0418/tomato-timer-widget/tree/feature/my-improvement) ![番茄计时器](https://img.shields.io/github/last-commit/Userwei0418/tomato-timer-widget)
  改进版 Trilium 番茄钟插件：在原作者基础上新增了显示/隐藏控制，并对界面进行了美化。
* [trilium-auto-hide-info-bar](https://github.com/SiriusXT/trilium-auto-hide-info-bar) ![trilium-auto-hide-info-bar](https://img.shields.io/github/last-commit/SiriusXT/trilium-auto-hide-info-bar)
  自动隐藏标题栏和信息栏，可单独设置隐藏其中之一。
* [trilium-back-to-history](https://github.com/SiriusXT/trilium-back-to-history) ![trilium-back-to-history](https://img.shields.io/github/last-commit/SiriusXT/trilium-back-to-history)
  跳转到上次浏览位置
* [trilium-jsmind](https://github.com/waterovo/trilium-jsmind) ![trilium-jsmind](https://img.shields.io/github/last-commit/waterovo/trilium-jsmind)
  在trilium创建[jsmind](https://github.com/hizzgdev/jsmind)思维导图。
* [trilium-left-panel-auto-zoom](https://github.com/SiriusXT/trilium-left-panel-auto-zoom) ![trilium-left-panel-auto-zoom](https://img.shields.io/github/last-commit/SiriusXT/trilium-left-panel-auto-zoom)
  通过移动鼠标自动扩展笔记树。适用于导航具有长标题和深层次笔记的便捷小部件。
* [trilium-remember-right-pane](https://github.com/SiriusXT/trilium-remember-right-pane) ![trilium-remember-right-pane](https://img.shields.io/github/last-commit/SiriusXT/trilium-remember-right-pane)
  允许在关闭右侧面板后点击按钮再次打开。通过标签记住右侧面板的状态。
* [trilium-simple-mind-map](https://github.com/waterovo/trilium-simple-mind-map) ![trilium-simple-mind-map](https://img.shields.io/github/last-commit/waterovo/trilium-simple-mind-map)
  在trilium创建[simple-mind-map](https://github.com/wanglin2/mind-map)思维导图。
* [trilium-show-position-in-toc](https://github.com/SiriusXT/trilium-show-position-in-toc) ![trilium-show-position-in-toc](https://img.shields.io/github/last-commit/SiriusXT/trilium-show-position-in-toc)
  在目录中标记当前浏览位置的字体为红色。
* [Trilium-TocWidget](https://github.com/Lolabird/Trilium-TocWidget) ![Trilium-TocWidget](https://img.shields.io/github/last-commit/Lolabird/Trilium-TocWidget)
  目录小部件现在是 Trilium Notes
  的内置功能。特别感谢开发者 [antoniotejada](https://github.com/antoniotejada/Trilium-TocWidget)
  和 [Lolabird](https://github.com/Lolabird/Trilium-TocWidget)！
* [trilium-fast-player](https://github.com/Userwei0418/trilium-fast-player) ![trilium-fast-player](https://img.shields.io/github/last-commit/Userwei0418/trilium-fast-player)
  在 Trilium 中嵌入并播放外部视频（本地 MP4、Bilibili、YouTube）


## 🪄 脚本

神奇！这些代码笔记通常在 Trilium 中标记为 JS 前端。它们通常带有 `#run=frontendStartup` 标签，以便在 Trilium
启动时自动执行。请记住，脚本是可执行代码，谨慎处理！

* [更好的包含](https://github.com/salmund/trilium_better_include) ![更好的包含](https://img.shields.io/github/last-commit/salmund/trilium_better_include)
  快速创建子笔记并进行包含操作
* [日历与课程表](https://github.com/Mangiola/trilium-scripts) ![日历与课程表](https://img.shields.io/github/last-commit/Mangiola/trilium-scripts)
  实现了日历、课程表，甚至还有音乐琴颈。
* [以星期日为首的日历](https://github.com/zadam/trilium/discussions/4540)
  在日历中将星期日设定为第一天。
* [Dark-mode-img-color-conversion](https://github.com/zadam/trilium/discussions/4209)
  调整网页上的图像和背景颜色以适应暗黑主题。
* [字体格式快捷键](https://github.com/zadam/trilium/issues/2954#issuecomment-1672431589)
  可自定义的 CKEditor 文本格式快捷键。显著提升编辑效率。
* [gistMirror](https://github.com/jwhonce/trilium-addons/blob/main/gistMirror/gistMirror.js) ![gistMirror](https://img.shields.io/github/last-commit/jwhonce/trilium-addons)
  将 GitHub Gists 镜像到 Trilium 笔记树
* [移动端视图](https://github.com/BeatLink/trilium-scripts/tree/main/Mobile%20View) ![移动端视图](https://img.shields.io/github/last-commit/BeatLink/trilium-scripts)
  这套脚本允许您在移动设备上使用 Trilium 服务器用户界面的全部功能。
    * [始终桌面模式](https://github.com/Nriver/trilium-translation/issues/90) 
      在移动设备上始终使用桌面用户界面。
* [在分割视图中打开笔记](https://github.com/zadam/trilium/discussions/3937)
  使用 Shift+点击在分割视图中打开笔记。Ctrl+Shift+点击用于树节点。
* [打开文件路径](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) ![打开文件路径](https://img.shields.io/github/gist/last-commit/de1f386fac9f9e797fd77022d63967c9)
  双击打开斜体显示的文件或文件夹路径
* [启动信息](https://github.com/Nriver/trilium-translation/blob/main/demo-cn/示例笔记%20-%20请不要删除/Trilium%20扩展/Trilium%20脚本%20script/startup%20启动项/startup%20message%20启动信息.js)
  ![启动信息](https://img.shields.io/github/last-commit/Nriver/trilium-translation)
  一个非常简单的脚本。显示随机信息。设置 `#run=frontendStartup` 以在 Trilium 启动时运行。就像每日一句（Message of the
  day）信息 :)
* [Trillium 日程](https://github.com/BeatLink/trilium-agenda) ![Trillium 日程](https://img.shields.io/github/last-commit/BeatLink/trilium-agenda)
  将待办事项分类为六个类别：逾期、今天、本周、本月、今年、未来
* [Trilium 聊天](https://github.com/soulsands/trilium-chat) ![Trilium 聊天](https://img.shields.io/github/last-commit/soulsands/trilium-chat)
  Trilium 的聊天插件目前支持 ChatGPT
* [trilium-next-image-lightbox](https://github.com/npgwgmggta/trilium-next-image-lightbox)
  Trilium Next 强大的图片灯箱查看器。双击笔记中的图片即可打开全屏灯箱，支持缩放、拖拽、当前笔记内图片切换、复制/导出、图片信息查看、右键菜单等功能。
* [Trilium-DailyMood](https://github.com/dvai/Trilium-DailyMood) ![Trilium-DailyMood](https://img.shields.io/github/last-commit/dvai/Trilium-DailyMood)
  在日历中浏览每日心情

---

## 💥 扩展 HTML 笔记

增强的 HTML 显示笔记通常包含复杂的功能，并通常使用 `~renderNote` 关系呈现复杂的独立 HTML 页面，超越小面板的功能。

* [drawio](https://github.com/SiriusXT/trilium-drawio) ![drawio](https://img.shields.io/github/last-commit/SiriusXT/trilium-drawio)
  集成的 drawio 插件
* [LaTeXPreview](https://github.com/rauenzi/Trilium-LaTeXPreview) ![LaTeXPreview](https://img.shields.io/github/last-commit/rauenzi/Trilium-LaTeXPreview)
  用于 Trilium Notes 的 LaTeX 笔记预览小部件
* [MarkdownPreview](https://github.com/rauenzi/Trilium-MarkdownPreview) ![MarkdownPreview](https://img.shields.io/github/last-commit/rauenzi/Trilium-MarkdownPreview)
  实时预览支持锚点、图片和同步滚动的 Markdown 文件
* [trilium-collection-views](https://github.com/mabeyj/trilium-collection-views) ![trilium-collection-views](https://img.shields.io/github/last-commit/mabeyj/trilium-collection-views)
  以不同方式显示笔记的出色扩展
* [Trilium-Heatmap](https://github.com/dvai/Trilium-Heatmap) ![Trilium-Heatmap](https://img.shields.io/github/last-commit/dvai/Trilium-Heatmap)
  在 Trilium 笔记中显示笔记修改热力图
* [Trilium JSON Editor](https://github.com/sottey/tje) ![Trilium JSON Editor](https://img.shields.io/github/last-commit/sottey/tje)
  用于 Trilium 的 JSON 笔记编辑器
* [Trilium-SingleFile](https://github.com/rauenzi/Trilium-SingleFile) ![Trilium-SingleFile](https://img.shields.io/github/last-commit/rauenzi/Trilium-SingleFile)
  用于轻松导入 SingleFile 存档的 Trilium 插件
* [看板视图](https://github.com/CyrilLeblanc/trilium-kanban) ![看板视图](https://img.shields.io/github/last-commit/CyrilLeblanc/trilium-kanban)
  适用于 Trilium Notes 的看板集成
* [收藏夹面板](https://github.com/youli42/Trilium-Favourite) ![收藏夹面板](https://img.shields.io/github/last-commit/youli42/Trilium-Favourite)
  一个收藏夹面板插件，将带有指定标签（默认 `#favourite`）的笔记以卡片网格展示，支持标签筛选、文字搜索、分页、自定义图标和颜色高亮。
* [Gantt TODO 面板](https://github.com/youli42/Trilium-TodoList) ![Gantt TODO 面板](https://img.shields.io/github/last-commit/youli42/Trilium-TodoList)
  基于 Frappe Gantt 的任务管理面板，提供甘特图、任务列表、设置三个标签页。支持 `#S-`/`#E-` 日期、`#P1`~`#P4` 优先级、重复任务、跟进标记等标准任务语法。
* [标签搜索](https://github.com/youli42/Trilium-TagSearch) ![标签搜索](https://img.shields.io/github/last-commit/youli42/Trilium-TagSearch)
  在笔记上方展示热门标签列表，点击标签名或标签值筛选笔记。支持全文搜索、精确/模糊匹配、分页、搜索历史，标签按频率和历史加权排序。

---

## 📱 移动端

与手机相关的酷炫功能。

### 🤖 Android

* [Pocket Trilium](https://github.com/nriver/pocket-trilium) ![pocket-trilium](https://img.shields.io/github/last-commit/nriver/pocket-trilium)
  全功能的安卓Trilium应用。可以离线运行并且能和Trilium服务器同步。
* [在 Android 上在 Termux 中运行 Trilium 服务器](https://github.com/zadam/trilium/discussions/4542) 你手中的服务器。
  玩得开心 :)
* [在 Android 的 Termux 上运行 TriliumNext 服务器](https://github.com/orgs/TriliumNext/discussions/5992)  
  将 TriliumNext 的强大功能掌握在您手中。
* [trilium-sender](https://github.com/zadam/trilium-sender) ![trilium-sender](https://img.shields.io/github/last-commit/zadam/trilium-sender)
  一个简单的仅写入的 Android 应用，用于将图片和笔记发送到 Trilium
* [TriliumDroid](https://github.com/FliegendeWurst/TriliumDroid) ![TriliumDroid](https://img.shields.io/github/last-commit/FliegendeWurst/TriliumDroid)  
  Trilium 的非官方 Android 移植版本，目前处于测试阶段。
* [Trilium-termux](https://github.com/jasongwq/Trilium-termux) ![trilium-sender](https://img.shields.io/github/last-commit/jasongwq/Trilium-termux)
   Termux 里运行的 Trilium. 自动跟踪最新版trilium发布.

### 🍎 iOS

* [trilium-ios-shortcut](https://github.com/soulsands/trilium-ios-shortcut) ![trilium-ios-shortcut](https://img.shields.io/github/last-commit/soulsands/trilium-ios-shortcut)
  通过 Apple 快捷方式向 Trilium 发送消息的教程。

---

## 🧚 API 扩展

更多的魔法！

注意！此类别中的插件涉及自定义请求处理程序（用户定义的 API）。请谨慎使用！

* [singlefile2trilium](https://github.com/nil0x42/singlefile2trilium) ![singlefile2trilium](https://img.shields.io/github/last-commit/nil0x42/singlefile2trilium)
  利用 [SingleFile](https://github.com/gildas-lormeau/SingleFile) 网页扩展的强大功能，您可以在 Trilium 中获得网页的完美副本。

---

## 🖥️ ETAPI

Trilium 的外部 API（也称为 [ETAPI](https://github.com/zadam/trilium/wiki/ETAPI)）相关的内容。

### 🦾 ETAPI 客户端

ETAPI 的客户端实现。

* [trilium-py](https://github.com/Nriver/trilium-py) ![trilium-py](https://img.shields.io/github/last-commit/Nriver/trilium-py)
  Trilium Note 的 ETAPI 的 Python 客户端，具有一些额外的酷炫功能。
* [pytrilium](https://github.com/perfectra1n/pytrilium) ![pytrilium](https://img.shields.io/github/last-commit/perfectra1n/pytrilium)
  Trilium Notes 的 ETAPI 的 Python 客户端，包含所有当前有效的 ETAPI 路径，并实现了自定义的 `requests` 会话。
* [trilium-alchemy](https://github.com/mm21/trilium-alchemy) ![trilium-alchemy](https://img.shields.io/github/last-commit/mm21/trilium-alchemy)
  Trilium Notes 的 Python SDK 和 CLI 工具包。
* [trilium-etapi](https://github.com/rauenzi/trilium-etapi) ![trilium-etapi](https://img.shields.io/github/last-commit/rauenzi/trilium-etapi)
  用于 Trilium Notes 的 ETAPI 的 Node.js 封装。

### 🤖 ETAPI 程序

基于 Trilium ETAPI 的程序。

* [omnivore2trilium](https://github.com/0xbismarck/omnivore2trilium) ![omnivore2trilium](https://img.shields.io/github/last-commit/0xbismarck/omnivore2trilium)
  这是一个工具，可以直接将来自 [Omnivore](https://omnivore.app/)（一个稍后阅读应用程序）的摘要导入到 Trilium 中。
* [trilium-bot](https://github.com/Nriver/trilium-bot) ![trilium-bot](https://img.shields.io/github/last-commit/Nriver/trilium-bot)
  由 [trilium-py](https://github.com/Nriver/trilium-py) 提供支持的 Trilium 的演示 Telegram 机器人。
* [Trilium2typecho](https://gitee.com/gkm0/trilium2typecho)
  Trilium笔记自动同步到typecho。
* [zotero-trilium](https://github.com/paulusm/zotero-trilium) ![zotero-trilium](https://img.shields.io/github/last-commit/paulusm/zotero-trilium)
适用于 Zotero 参考管理器的附加组件，可让您将格式化的参考文献和注释导出到 Trilium。
* [trilium-blog](https://github.com/harveyTon/trilium-blog) ![trilium-blog](https://img.shields.io/github/last-commit/harveyTon/trilium-blog) 基于 Trilium Notes 的现代化轻量级博客系统，支持 Vue 3 前端和 Go 后端，使用 Docker 部署。
* [trilium-sender-bot](https://github.com/rainrisa/trilium-sender-bot) ![trilium-sender-bot](https://img.shields.io/github/last-commit/rainrisa/trilium-sender-bot)
  将来自 Telegram 的笔记直接发送到 Trilium。
* [Trilium_Telegram_bot](https://github.com/ktibr0/Trilium_telegram_bot) ![Trilium_Telegram_bot](https://img.shields.io/github/last-commit/ktibr0/Trilium_telegram_bot)
  直接通过 Telegram 将笔记和管理待办事项导入 Trilium。
---

## 🧩 Chrome 扩展程序

* [Trilium 网页剪藏器](https://github.com/zadam/trilium-web-clipper) ![Trilium Web Clipper](https://img.shields.io/github/last-commit/zadam/trilium-web-clipper)
  将网页内容保存到 Trilium Notes 中。

* [Trilium 网页剪藏器 Plus](https://github.com/Nriver/trilium-web-clipper-plus) ![Trilium Web Clipper Plus](https://img.shields.io/github/last-commit/Nriver/trilium-web-clipper-plus)
  Trilium 网页剪辑器的分支版本，适配了 Chrome Manifest V3。

---

## 👨‍💻 开发工具

用于开发 Trilium 及其插件的开发工具。

* [trilium-pack](https://github.com/rauenzi/trilium-pack) ![trilium-pack](https://img.shields.io/github/last-commit/rauenzi/trilium-pack)
  一个简单的将附加组件打包为 Trilium Notes `zip` 文件的方法。
* [trilium-types](https://github.com/rauenzi/trilium-types) ![trilium-types](https://img.shields.io/github/last-commit/rauenzi/trilium-types)
  用于 Trilium Notes 的 TypeScript `@types` 包。

---

## 📚 维基和文档

* [官方维基](https://github.com/zadam/trilium/wiki)
  Trilium 的官方维基。
* [中文维基](https://github.com/baddate/trilium-wiki)
  官方维基的中文翻译。

---

## 🌐 翻译

Trilium Notes 的第三方翻译。

* [trilium-translation](https://github.com/Nriver/trilium-translation) ![trilium-translation](https://img.shields.io/github/last-commit/Nriver/trilium-translation)
  Trilium 的非官方翻译项目。目前已完成中文翻译。

## 🔥 贡献

欢迎 fork 并贡献到这个仓库。

[目录](#table-of-contents)
部分由 [https://github.com/ekalinin/github-markdown-toc](https://github.com/ekalinin/github-markdown-toc) 生成。然后在
PyCharm 中通过 `Ctrl + Alt + L` 进行重新格式化。
