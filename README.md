# 😎 awesome-trilium

<p align="center">
English | <a href="README_CN.md">简体中文</a>
</p>

A curated list of awesome [Trilium Notes](https://github.com/zadam/trilium) extensions. Including themes, widgets,
scripts, API extensions, ETAPI, etc.

You are welcome to add cool stuff about Trilium Notes here.

--------------------

## 🦮 Table of Contents

<!--ts-->
* [😎 awesome-trilium](#-awesome-trilium)
   * [🦮 Table of Contents](#-table-of-contents)
   * [📥 Migrating to Trilium](#-migrating-to-trilium)
   * [🏡 Themes](#-themes)
   * [✂️ CSS Snippets](#-css-snippets)
   * [⚙️ Widgets](#-widgets)
   * [🪄 Scripts](#-scripts)
   * [💥 Extension HTML Note](#-extension-html-note)
   * [📱 Mobile](#-mobile)
      * [🤖 Android](#-android)
      * [🍎 iOS](#-ios)
   * [🧚 API extensions](#-api-extensions)
   * [🖥️ ETAPI](#-etapi)
      * [🦾 ETAPI client](#-etapi-client)
      * [🤖 ETAPI programs](#-etapi-programs)
   * [🧩 Chrome Extensions](#-chrome-extensions)
   * [👨‍💻 Development Tools](#-development-tools)
   * [📚 Wikis &amp; documents](#-wikis--documents)
   * [🌐 Translation](#-translation)
   * [🔥 Contribution](#-contribution)
   <!--te-->

---

## 📥 Migrating to Trilium

These scripts and tips can be used to migrate to Trilium from other note taking applications:

* [Evernote](https://github.com/zadam/trilium/wiki/Evernote-import) (Trilium Wiki Guide) The most recent version of the
  Evernote application no longer includes the option to export files as an enex file. Instead, it now offers a different
  encrypted dump file format, which no one else can read. If you want to obtain an enex file, you might need to utilize
  the following tool: https://github.com/vzhd1701/evernote-backup.
* [HTML](https://github.com/zadam/trilium/wiki/Markdown) Supported Natively
* [Joplin](https://github.com/Nriver/trilium-py#import-from-joplin) Can be imported with trilium-py.
* [Logseq](https://github.com/Nriver/trilium-py#import-from-logseq) Can be imported with trilium-py.
* [Markdown](https://github.com/zadam/trilium/wiki/Markdown) Supported Natively
* [Obsidian](https://github.com/Nriver/trilium-py#import-from-obsidian) Need to convert a Obsidian vault to regular
  Markdown files first. Then import with trilium-py to handle obisdian's unique linking format. See more in the link.
* [OneNote](https://github.com/zadam/trilium/wiki/Onenote) (Trilium Wiki Guide)
* [Text](https://github.com/zadam/trilium/wiki/Markdown) Supported Natively
* [Turtl](https://github.com/Nriver/trilium-py/tree/main/examples/turtl-to-markdown) Convert Turtl notes to markdown
  directory
* [Youdao Note/有道云笔记](https://github.com/Nriver/trilium-py#import-from-youdao-note%E6%9C%89%E9%81%93%E4%BA%91%E7%AC%94%E8%AE%B0)
  Requires to download notes and convert to markdown. More details are in the link.
* [VNote](https://github.com/Nriver/trilium-py#import-from-vnote) Can be imported with trilium-py. The special image
  format will be well handled.
* [Zotero](https://github.com/paulusm/zotero-trilium) A Zotero plugin to export notes to Trillium notes
* .OPML Contents can be read and imported natively
* .TAR Contents can be read and imported natively
* .ZIP Contents can be read and imported natively

---

## 🏡 Themes

**App Themes**

App Themes provide theming to the Trilium application. Typically, these notes are labeled with `#appTheme` with a value
which indicates the name of the theme displayed in Trilium's options panel.

* [Allure Theme](https://github.com/JadeVane/Allure) ![Allure](https://img.shields.io/github/last-commit/Nriver/bing-daily-theme)
  A more beautiful and simple theme for trilium.
* [Bing Daily Theme](https://github.com/Nriver/bing-daily-theme) ![Bing Daily Theme](https://img.shields.io/github/last-commit/Nriver/bing-daily-theme)
  Automatically receive the Bing daily wallpaper every day for Trilium.
* [Blue Theme](https://github.com/SiriusXT/trilium-theme-blue) ![Blue Theme](https://img.shields.io/github/last-commit/SiriusXT/trilium-theme-blue)
  A brilliant and beautiful theme. Thanks SiriusXT!
* [breeze-trilium](https://github.com/eliandoran/breeze-trilium) ![breeze-trilium](https://img.shields.io/github/last-commit/eliandoran/breeze-trilium)
  KDE Breeze theme for Trilium Notes
* [Catppuccin](https://github.com/SadAlexa/trilium-theme-catppuccin) ![Catppuccin](https://img.shields.io/github/last-commit/SadAlexa/trilium-theme-catppuccin)
  A theme for Trilium Notes, made with Catppuccin palette.
* [Chameleon Theme](https://github.com/DavidFuchs/trilium-chameleon-theme) ![Chameleon Theme](https://img.shields.io/github/last-commit/DavidFuchs/trilium-chameleon-theme)
  A set of light and dark colour themes for Trilium.
* [EverForest Ant Dark (EFAD) Trilium Theme](https://github.com/Lolabird/everforest-ant-dark-trilium-theme) ![EverForest Ant Dark (EFAD) Trilium Theme](https://img.shields.io/github/last-commit/Lolabird/everforest-ant-dark-trilium-theme)
  Trilium Notes theme to go with Everforest and Ant Dark linux desktop themes.
* [Lightpad](https://github.com/ohmstance/trilium-lightpad-theme) ![Lightpad](https://img.shields.io/github/last-commit/ohmstance/trilium-lightpad-theme)
  A light theme with numerous user-friendly adjustments, greatly enhancing the mobile experience.
* [Linen Theme](https://github.com/mondayrobot/trilium-linen-theme) ![Linen Theme](https://img.shields.io/github/last-commit/mondayrobot/trilium-linen-theme)
  A minimal, airy light theme for Trilium with an optional distraction-free mode.
* [Melon Theme](https://github.com/raphwriter/trilium-theme-melon) ![Melon Theme](https://img.shields.io/github/last-commit/raphwriter/trilium-theme-melon)
  A delightful theme.
* [Lemon Tree](https://github.com/yu-jingrui/trilium-theme-lemon-tree) ![Lemon Tree](https://img.shields.io/github/last-commit/yu-jingrui/trilium-theme-lemon-tree)
  A delightful theme based on trilium-next-light, inspired by Melon Theme.  
* [Mist-Moon](https://github.com/Ivy-End/Mist-Moon) ![Mist-Moon](https://img.shields.io/github/last-commit/Ivy-End/Mist-Moon)
  A Light Theme inspired by mist moon night view.
* [NieR-Automata Theme](https://github.com/Nriver/NieR-Automata-Trilium-Theme) ![NieR-Automata Theme](https://img.shields.io/github/last-commit/Nriver/NieR-Automata-Trilium-Theme)
  A fan-made NieR-Automata game UI like theme. This theme is made by me :)
* [Obsidian Theme](https://github.com/greengeek/trilium-obsidian-theme) ![Obsidian Theme](https://img.shields.io/github/last-commit/greengeek/trilium-obsidian-theme)
    Dark theme with minor purple highlights for Trilium Notes
    * [Trilium Greensidian Theme](https://github.com/obuno/trilium-greensidian-theme) ![Trilium Greensidian Theme](https://img.shields.io/github/last-commit/obuno/trilium-greensidian-theme)
      Green color version of Obsidian Theme
* [Solarized theme](https://github.com/WKSu/trilium-solarized-theme) ![Solarized theme](https://img.shields.io/github/last-commit/WKSu/trilium-solarized-theme)
  Brings the classic solarized themes to Trilium! It comes in both light and dark.
* [Stellar Dark Theme](https://github.com/Lolabird/stellar-dark-theme-trilium) ![Stellar Dark Theme](https://img.shields.io/github/last-commit/Lolabird/stellar-dark-theme-trilium)
  A different taste of dark theme.
* [VSCode-Dark Theme](https://github.com/greengeek/trilium-vscode-dark-theme) ![VSCode-Dark Theme](https://img.shields.io/github/last-commit/greengeek/trilium-vscode-dark-theme)
  It's VSCode!
* [Ra1n's Dark Theme](https://github.com/perfectra1n/custom-trilium-themes) ![Ra1n's Dark Theme](https://img.shields.io/github/last-commit/perfectra1n/custom-trilium-themes)
  Dark theme that looks good and is easy on the eyes!
* [eva theme](https://github.com/cocolight/trilium-theme-eva) ![eva Theme](https://img.shields.io/github/last-commit/cocolight/trilium-theme-eva)
  A theme that brings the style of the Eva theme plugin to VSCode, including eva-light, eva-dark, and eva-night.

**Sharing Themes**

Sharing themes provide theming to shared notes! A sharing note can use custom theme by using `~shareCss` relation to a
css note. See [Styling the shared notes](https://github.com/zadam/trilium/wiki/Sharing#styling-the-shared-notes) for
more info.

* [Ankia-Theme](https://github.com/dvai/Ankia-Theme) ![Ankia-Theme](https://img.shields.io/github/last-commit/dvai/Ankia-Theme)
  A card-style Trilium blog theme.
* [FrostMiKu/Share.CSS](https://github.com/FrostMiKu/Share.CSS) ![FrostMiKu/Share.CSS](https://img.shields.io/github/last-commit/FrostMiKu/Share.CSS)
  A nice and clean theme for sharing notes. You should try it!
* [uweizh/trilium-sharecss](https://github.com/uweizh/trilium-sharecss) ![uweizh/trilium-sharecss](https://img.shields.io/github/last-commit/uweizh/trilium-sharecss)
  A gradient color theme for shareing.
* [WhiteMinimalist-Theme](https://github.com/Shmaur/WhiteMinimalist-Theme) ![WhiteMinimalist-Theme](https://img.shields.io/github/last-commit/Shmaur/WhiteMinimalist-Theme)
  A WhiteMinimalist Theme blog theme.
* [ysslang's theme](https://github.com/zadam/trilium/discussions/2681) ![ysslang's theme](https://img.shields.io/github/gist/last-commit/46e2a57ca95ba9c7368cbd255d1ac769)
  Paper with shadow effect, cool!
* [trilium.rocks theme](https://github.com/perfectra1n/trilium.rocks/releases/tag/1.0.0) ![trilium.rocks theme](https://img.shields.io/github/last-commit/perfectra1n/trilium.rocks)
  This uses the same theme that's used on the [trilium.rocks](https://trilium.rocks/) site from @zerebos. The link above also includes the instructions on how it can be installed. Can also be created from scratch [here](https://trilium.rocks/xecUJ8eL3pvM).
* [Akari-Theme](https://github.com/march-7th-mini/Trilium-X-Akari) ![Akari-Theme](https://img.shields.io/github/last-commit/march-7th-mini/Trilium-X-Akari)
  Based on the Ankia and WhiteMinimalist themes, it includes a beautified homepage, embedded Kimi Chat, mask color settings, collapsible unordered lists and code blocks, a searchable and collapsible table of contents, Sakana! Widget, background music, a fully expanded navigation menu, localized MathJax right-click menu, hover-to-zoom emoji previews in comments, more pages with background image settings, and bug fixes.
---

## ✂️ CSS Snippets

Custom CSS is used to alter the appearance of Trilium. These code snippets are typically labeled with `#appCss`.
See ([Trilium Wiki](https://github.com/zadam/trilium/wiki/Themes#custom-css)
for instructions on how to enable custom CSS)

* [active calendar days visibility improvement](https://github.com/Nriver/awesome-trilium/issues/30)
* [display edited notes as list](https://github.com/zadam/trilium/discussions/2670#discussion-3884786)
* [horizontal scrollbar](https://github.com/zadam/trilium/discussions/4706) A css snippet to make the left panel and toc display a horizontal scrollbar.
* [images with transparent background](https://github.com/TriliumNext/Notes/issues/361) Add transparent background for transparent images.
* [remove numbers from table of contents](https://github.com/zadam/trilium/discussions/3873#discussioncomment-5710601)
* [trilium-enhancement](https://github.com/Nriver/trilium-enhancement) ![trilium-enhancement](https://img.shields.io/github/last-commit/Nriver/trilium-enhancement) Experience Enhancement Kit for Trilium Notes.
* [Trilium-TextNoteEnhancement](https://github.com/SiriusXT/Trilium-TextNoteEnhancement) ![Trilium-TextNoteEnhancement](https://img.shields.io/github/last-commit/SiriusXT/Trilium-TextNoteEnhancement)
  Some widgets enhance trilium text input efficiency.
* [vertical lines for tree](https://github.com/zadam/trilium/issues/3892#issuecomment-1530144842)
* [zen mode](https://github.com/Nriver/awesome-trilium/issues/44) Add zen mode to your Trilium.
* [trilium-enhancement-Lazy-Pack](https://github.com/march-7th-mini/trilium-enhancement-Lazy-Pack) ![trilium-enhancement-Lazy-Pack](https://img.shields.io/github/last-commit/march-7th-mini/trilium-enhancement-Lazy-Pack)
  Trilium Notes v0.63.7 curated power-user pack: VOCALoid idol color theme, read-only zoom/drag/preview, iframe Kimi-Chat + 18 more tweaks.

---

## ⚙️ Widgets

Widgets can make big difference in the Trilium user experience!

A widget typically alters Trilium's user interface and offers additional panel functionalities. The primary JavaScript
file of a widget is usually labeled with `#widget`.

* [AI Voice Note Widget](https://github.com/Userwei0418/trilium_AI_Voice_Note-) ![AI Voice Note Widget](https://img.shields.io/github/last-commit/Userwei0418/trilium_AI_Voice_Note-)
  A fully-featured speech-to-text and intelligent organization widget for Trilium Notes.
* [Breadcrumbs](https://github.com/rauenzi/Trilium-Breadcrumbs) ![Breadcrumbs](https://img.shields.io/github/last-commit/rauenzi/Trilium-Breadcrumbs)
  Shows note breadcrumbs at the bottom of the page
* [command-palette](https://github.com/justyns/trilium-scripts) ![command-palette](https://img.shields.io/github/last-commit/justyns/trilium-scripts)
  Simple command-palette for Trilium
* [Convert formulas in Note](https://github.com/zadam/trilium/discussions/4792) 
  Convert math formulas wrapped in single dollar signs `$` and double dollar signs `$$` into HTML format within Trilium Notes
* [Copy Code Block](https://github.com/Nriver/copy-code-block-widget) ![command-palette](https://img.shields.io/github/last-commit/Nriver/copy-code-block-widget)
  Double click to copy code block
* [Countdown Days](https://github.com/Nriver/countdown-days-widget) ![Countdown Days](https://img.shields.io/github/last-commit/Nriver/countdown-days-widget)
  Add a relative days message under journal note title.
* [hexmap](https://gitlab.com/QuentinLeCaignec/trilium-hexmap) ![hexmap](https://img.shields.io/gitlab/last-commit/QuentinLeCaignec/trilium-hexmap)
  Interactive hexmap (for TTRPGs)
* [Image zoom](https://github.com/Nriver/image-zoom-widget) ![Image zoom](https://img.shields.io/github/last-commit/Nriver/image-zoom-widget)
  Zoom, drag, and preview images in Trilium
  * [MusicPlayer](https://github.com/Userwei0418/trilium-MusicPlayer) ![MusicPlayer](https://img.shields.io/gitlab/last-commit/Userwei0418/trilium-MusicPlayer)
  A simple music player that supports play/pause, volume control, playback order adjustment, and show/hide toggling
* [Knowledge Card Gallery](https://github.com/Userwei0418/trilium_Knowledge-Gallery-Viewer) ![Knowledge Card Gallery](https://img.shields.io/github/last-commit/Userwei0418/trilium_Knowledge-Gallery-Viewer)
  An immersive knowledge internalization tool designed for Trilium Notes. It transforms dry note text into visual "knowledge cards" and "flashcards," and integrates AI-powered extraction features to help you quickly organize key insights and perform spaced repetition reviews.
* [Magic Toolbox](https://github.com/Userwei0418/trilium-Magic-Toolbox) ![Magic Toolbox](https://img.shields.io/github/last-commit/Userwei0418/trilium-Magic-Toolbox)
  Turn your Trilium into a lightweight OS, make scripts working like `mini apps`.
* [openfilepath](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) ![openfilepath](https://img.shields.io/github/gist/last-commit/de1f386fac9f9e797fd77022d63967c9)
  Opens italicised file path upon double click
* [Scratchpad](https://github.com/zadam/trilium/discussions/1613#discussioncomment-638984)
  Add scratchpad widget to notes
* [Syntax Highlight](https://github.com/antoniotejada/Trilium-SyntaxHighlightWidget) ![Syntax Highlight](https://img.shields.io/github/last-commit/antoniotejada/Trilium-SyntaxHighlightWidget)
  The syntax highlight feature which you would like.
* [Swap enter](https://github.com/Nriver/swap-enter-widget) ![Swap enter](https://img.shields.io/github/last-commit/Nriver/swap-enter-widget)
  Swap "enter" and "shift + enter" for Trilium Notes.
* [Theme Switch](https://github.com/madodig/trilium-widget-theme-switch) ![Theme Switch](https://img.shields.io/github/last-commit/madodig/trilium-widget-theme-switch)
  Trilium widget for changing themes
* [timeline](https://gitlab.com/QuentinLeCaignec/trilium-timeline) ![timeline](https://img.shields.io/gitlab/last-commit/QuentinLeCaignec/trilium-timeline)
  Interactive timeline
* [tomato-timer](https://github.com/Nriver/tomato-timer-widget) ![tomato-timer](https://img.shields.io/github/last-commit/Nriver/tomato-timer-widget)
  Pomodoro timer for Trilium Notes
  * [tomato-timer](https://github.com/Userwei0418/tomato-timer-widget/tree/feature/my-improvement) ![tomato-timer](https://img.shields.io/github/last-commit/Userwei0418/tomato-timer-widget)
  Enhanced Pomodoro timer widget for Trilium: adds show/hide controls and improves the UI based on the original version.
* [trilium-auto-hide-info-bar](https://github.com/SiriusXT/trilium-auto-hide-info-bar) ![trilium-auto-hide-info-bar](https://img.shields.io/github/last-commit/SiriusXT/trilium-auto-hide-info-bar)
  Automatically hide the title bar and information bar, and you can set to hide one of them individually.
* [trilium-back-to-history](https://github.com/SiriusXT/trilium-back-to-history) ![trilium-back-to-history](https://img.shields.io/github/last-commit/SiriusXT/trilium-back-to-history)
  Jump to the last browsing position
* [trilium-dnd-dice](https://github.com/AzzyB/trilium-dnd-dice) ![trilium-dnd-dice](https://img.shields.io/github/last-commit/AzzyB/trilium-dnd-dice) D20 system/General Dice roller widget
* [trilium-jsmind](https://github.com/waterovo/trilium-jsmind) ![trilium-jsmind](https://img.shields.io/github/last-commit/waterovo/trilium-jsmind)
  Create [jsmind](https://github.com/hizzgdev/jsmind) mindmap in Trilium.
* [trilium-left-panel-auto-zoom](https://github.com/SiriusXT/trilium-left-panel-auto-zoom) ![trilium-left-panel-auto-zoom](https://img.shields.io/github/last-commit/SiriusXT/trilium-left-panel-auto-zoom)
  Automatically widen note tree by moving your mouse. A convenient widget to navigate through notes with long titles and
  deep level notes.
* [trilium-remember-right-pane](https://github.com/SiriusXT/trilium-remember-right-pane) ![trilium-remember-right-pane](https://img.shields.io/github/last-commit/SiriusXT/trilium-remember-right-pane)
  Lets you click a button to open the right pane again after closing it. Remembers the right pane state by label.
* [trilium-show-position-in-toc](https://github.com/SiriusXT/trilium-show-position-in-toc) ![trilium-show-position-in-toc](https://img.shields.io/github/last-commit/SiriusXT/trilium-show-position-in-toc)
  Mark font red of the position being browsed in the Table of contents.
* [trilium-simple-mind-map](https://github.com/waterovo/trilium-simple-mind-map) ![trilium-simple-mind-map](https://img.shields.io/github/last-commit/waterovo/trilium-simple-mind-map)
  Create [simple-mind-map](https://github.com/wanglin2/mind-map) mindmap in Trilium.
* [Trilium-TocWidget](https://github.com/Lolabird/Trilium-TocWidget) ![Trilium-TocWidget](https://img.shields.io/github/last-commit/Lolabird/Trilium-TocWidget)
  The table of content widget is now a built-in feature in Trilium Notes. Great thank to
  developers [antoniotejada](https://github.com/antoniotejada/Trilium-TocWidget)
  and [Lolabird](https://github.com/Lolabird/Trilium-TocWidget) !
* [trilium-fast-player](https://github.com/Userwei0418/trilium-fast-player) ![trilium-fast-player](https://img.shields.io/github/last-commit/Userwei0418/trilium-fast-player)
  A streamlined way to embed and play external videos (Local MP4, Bilibili, YouTube) in Trilium

---

## 🪄 Scripts

Magic! These code notes are typically tagged as JS frontend in Trilium.
They're often marked with `#run=frontendStartup` for automatic execution when Trilium starts.
Remember, scripts are executable codes. Handle with caution!

* [Better Include](https://github.com/salmund/trilium_better_include) ![Better Include](https://img.shields.io/github/last-commit/salmund/trilium_better_include)
  Make subnotes and include them faster
* [Calendar & Timetable](https://github.com/Mangiola/trilium-scripts) ![Calendar & Timetable](https://img.shields.io/github/last-commit/Mangiola/trilium-scripts)
  Implements a calendar, timetable, and even a musical fretboard.
* [Calendar Sunday First](https://github.com/zadam/trilium/discussions/4540)
  Use Sunday as first weekday in calendar.
* [Dark-mode-img-color-conversion](https://github.com/zadam/trilium/discussions/4209)
  Adjusting the images and background colors on the web page to suit a dark theme.
* [Font formatting shortcuts](https://github.com/zadam/trilium/issues/2954#issuecomment-1672431589)
  Customizable shortcut keys for text formatting in CKEditor. Makes significant enhancement in editing efficiency.
* [gistMirror](https://github.com/jwhonce/trilium-addons/blob/main/gistMirror/gistMirror.js) ![gistMirror](https://img.shields.io/github/last-commit/jwhonce/trilium-addons)
  Mirror GitHub Gists to Trilium Note tree
* [Mobile View](https://github.com/BeatLink/trilium-scripts/tree/main/Mobile%20View) ![Mobile View](https://img.shields.io/github/last-commit/BeatLink/trilium-scripts)
  These set of scripts allow you to use the full capabilities of the Trilium server user interface while on a mobile
  device.
    * [always desktop mode](https://github.com/Nriver/trilium-translation/issues/90) 
      Always use desktop UI on mobile device.
* [Open note in split view](https://github.com/zadam/trilium/discussions/3937)
  Shift+click to open a note in split view. Ctrl+shift+click for tree nodes.
* [OpenFilePaths](https://gist.github.com/laundmo/de1f386fac9f9e797fd77022d63967c9) ![OpenFilePaths](https://img.shields.io/github/gist/last-commit/de1f386fac9f9e797fd77022d63967c9)
  Italicized file or folder paths can be opened with a double click
* [Reflective Journal Prompts](https://gist.github.com/paulusm/9f840a4ed59e4bfb2d2de6b004b429b1) ![Reflective Journal Prompts](https://img.shields.io/github/gist/last-commit/9f840a4ed59e4bfb2d2de6b004b429b1
) Insert a random journaling prompt in the current note (binds to ctrl+shift+p) 
* [Startup message](https://github.com/Nriver/trilium-translation/blob/main/demo-cn/示例笔记%20-%20请不要删除/Trilium%20扩展/Trilium%20脚本%20script/startup%20启动项/startup%20message%20启动信息.js)
  ![Startup message](https://img.shields.io/github/last-commit/Nriver/trilium-translation)
  A quite simple script. Display a random message. Set `#run=frontendStartup` to run it when Trilium startup. Just like
  a MOTD(Message of the day) message :)
* [Trillium Agenda](https://github.com/BeatLink/trilium-agenda) ![Trillium Agenda](https://img.shields.io/github/last-commit/BeatLink/trilium-agenda)
  Sorts todos into 6 categories: Overdue, Today, This Week, This Month, This Year, Future
* [Trilium-chat](https://github.com/soulsands/trilium-chat) ![Trilium-chat](https://img.shields.io/github/last-commit/soulsands/trilium-chat)
  Allows interaction with ChatGPT and Ollama conveniently right inside of Trilium.
* [Trilium-DailyMood](https://github.com/dvai/Trilium-DailyMood) ![Trilium-DailyMood](https://img.shields.io/github/last-commit/dvai/Trilium-DailyMood)
  Browse daily moods in the calendar
* [Beatlink's Trilium Scripts](https://github.com/BeatLink/trilium-scripts) A collection of scripts and widgets to do everything from allowing you to set priority colors on Notes, to scripting recurring To-dos.

---

## 💥 Extension HTML Note

An enhanced HTML display notes often incorporates complex features and commonly uses the `~renderNote` relation to
present intricate standalone HTML pages, surpassing the capabilities of small panels.

* [drawio](https://github.com/SiriusXT/trilium-drawio) ![drawio](https://img.shields.io/github/last-commit/SiriusXT/trilium-drawio)
  Integrated drawio plug-in
* [LaTeXPreview](https://github.com/rauenzi/Trilium-LaTeXPreview) ![LaTeXPreview](https://img.shields.io/github/last-commit/rauenzi/Trilium-LaTeXPreview)
  A widget for Trilium Notes to preview LaTeX notes
* [MarkdownPreview](https://github.com/rauenzi/Trilium-MarkdownPreview) ![MarkdownPreview](https://img.shields.io/github/last-commit/rauenzi/Trilium-MarkdownPreview)
  Live preview markdown files with support for anchors, images, and sync scroll
* [trilium-collection-views](https://github.com/mabeyj/trilium-collection-views) ![trilium-collection-views](https://img.shields.io/github/last-commit/mabeyj/trilium-collection-views)
  A great extension for displaying notes in a different way.
* [Trilium-Heatmap](https://github.com/dvai/Trilium-Heatmap) ![Trilium-Heatmap](https://img.shields.io/github/last-commit/dvai/Trilium-Heatmap)
  Display a note modification heatmap in a Trilium note
* [Trilium JSON Editor](https://github.com/sottey/tje) ![Trilium JSON Editor](https://img.shields.io/github/last-commit/sottey/tje)
  JSON Note editor for Trilium
* [Trilium-SingleFile](https://github.com/rauenzi/Trilium-SingleFile) ![Trilium-SingleFile](https://img.shields.io/github/last-commit/rauenzi/Trilium-SingleFile)
  An addon for Trilium to easily import SingleFile archives.
* [Kanban View](https://github.com/CyrilLeblanc/trilium-kanban) ![Kanban View](https://img.shields.io/github/last-commit/CyrilLeblanc/trilium-kanban)
  A Kanban integration for Trilium Notes

---

## 📱 Mobile

Mobile phone related cool stuff.

### 🤖 Android

* [Run Trilium Server in Termux on Android](https://github.com/zadam/trilium/discussions/4542) Your server in your hand.
  Have fun :)
* [Run TriliumNext Server in Termux on Android](https://github.com/orgs/TriliumNext/discussions/5992)
  Power of TriliumNext, in the palm of your hand.
* [trilium-sender](https://github.com/zadam/trilium-sender) ![trilium-sender](https://img.shields.io/github/last-commit/zadam/trilium-sender)
  A simple write-only android application for sending images and notes to Trilium
* [TriliumDroid](https://github.com/FliegendeWurst/TriliumDroid) ![TriliumDroid](https://img.shields.io/github/last-commit/FliegendeWurst/TriliumDroid)
  Unofficial port of Trilium to Android, in beta
* [Trilium-termux](https://github.com/jasongwq/Trilium-termux) ![trilium-sender](https://img.shields.io/github/last-commit/jasongwq/Trilium-termux)
  Trilium in termux. Auto check Trilium releases and publish.

### 🍎 iOS

* [trilium-ios-shortcut](https://github.com/soulsands/trilium-ios-shortcut) ![trilium-ios-shortcut](https://img.shields.io/github/last-commit/soulsands/trilium-ios-shortcut)
  A tutorial on sending messages to Trilium via an Apple shortcut.

---

## 🧚 API extensions

More magic!

Caution! The plugins in this category involves custom request handlers (user defined APIs). Use them with care!

* [singlefile2trilium](https://github.com/nil0x42/singlefile2trilium) ![singlefile2trilium](https://img.shields.io/github/last-commit/nil0x42/singlefile2trilium)
  With the power of [SingleFile](https://github.com/gildas-lormeau/SingleFile) web extension, you can get a perfect copy
  of the webpage in Trilium.

---

## 🖥️ ETAPI

Trilium's external API (aka [ETAPI](https://github.com/zadam/trilium/wiki/ETAPI)) related stuff.

### 🦾 ETAPI client

The client implementations for ETAPI.

* [trilium-py](https://github.com/Nriver/trilium-py) ![trilium-py](https://img.shields.io/github/last-commit/Nriver/trilium-py)
  Python client for ETAPI of Trilium Note with some extra cool features.
* [pytrilium](https://github.com/perfectra1n/pytrilium) ![pytrilium](https://img.shields.io/github/last-commit/perfectra1n/pytrilium)
  Python client for ETAPI of Trilium Notes that contains all currently valid ETAPI paths, and implements a custom
  underlying `requests` session.
* [trilium-alchemy](https://github.com/mm21/trilium-alchemy) ![trilium-alchemy](https://img.shields.io/github/last-commit/mm21/trilium-alchemy)
  Python SDK and CLI toolkit for Trilium Notes.
* [trilium-etapi](https://github.com/rauenzi/trilium-etapi) ![trilium-etapi](https://img.shields.io/github/last-commit/rauenzi/trilium-etapi)
  A Node.js wrapper around the ETAPI for Trilium Notes.

### 🤖 ETAPI programs

Programs based on triliums ETAPI.

* [libby2trilium](https://github.com/0xbismarck/libby2trilium) ![libby2trilium](https://img.shields.io/github/last-commit/0xbismarck/libby2trilium)
  Import your book highlights and notes from [Libby](https://libbyapp.com/) into Trilium Notes.
* [omnivore2trilium](https://github.com/0xbismarck/omnivore2trilium) ![omnivore2trilium](https://img.shields.io/github/last-commit/0xbismarck/omnivore2trilium)
  A tool that imports highlights directly into Trilium from [Omnivore](https://omnivore.app/), a Read-It-Later App.
* [triliumclipper](https://github.com/0xbismarck/ThunderbirdTriliumClipper) ![triliumclipper](https://img.shields.io/github/last-commit/0xbismarck/ThunderbirdTriliumClipper) A [Thunderbird](https://www.thunderbird.net) add-on that enables you to create notes from your e-mails from inside Thunderbird. 
* [trilium-blog](https://github.com/harveyTon/trilium-blog) ![trilium-blog](https://img.shields.io/github/last-commit/harveyTon/trilium-blog) 
  A modern and lightweight blog system based on Trilium Notes, supporting Vue 3 front-end and Go back-end, deployed using Docker.
* [trilium-bot](https://github.com/Nriver/trilium-bot) ![trilium-bot](https://img.shields.io/github/last-commit/Nriver/trilium-bot)
* [Trilium2typecho](https://gitee.com/gkm0/trilium2typecho)
  Sync Trilium Notes to typecho automatically.
  A demo Telegram bot for Trilium, powered by [trilium-py](https://github.com/Nriver/trilium-py).
* [zotero-trilium](https://github.com/paulusm/zotero-trilium) ![zotero-trilium](https://img.shields.io/github/last-commit/paulusm/zotero-trilium)
  Add-on for Zotero reference manager, lets you export formatted references and notes across to Trilium.
* [trilium-sender-bot](https://github.com/rainrisa/trilium-sender-bot) ![trilium-sender-bot](https://img.shields.io/github/last-commit/rainrisa/trilium-sender-bot)
  Send notes from Telegram straight into Trilium.

---

## 🧩 Chrome Extensions

* [Trilium Web Clipper](https://github.com/zadam/trilium-web-clipper) ![Trilium Web Clipper](https://img.shields.io/github/last-commit/zadam/trilium-web-clipper)
  Save web clippings to Trilium Notes.
* [Trilium Web Clipper Plus](https://github.com/Nriver/trilium-web-clipper-plus) ![Trilium Web Clipper Plus](https://img.shields.io/github/last-commit/Nriver/trilium-web-clipper-plus)
  Fork of Trilium Web Clipper. Adapted to Chrome Manifest V3.

---

## 👨‍💻 Development Tools

Development tools for developing Trilium and its plugins.

* [trilium-pack](https://github.com/rauenzi/trilium-pack) ![trilium-pack](https://img.shields.io/github/last-commit/rauenzi/trilium-pack)
  A simple way to pack addons as `zip` files for Trilium Notes.
* [trilium-types](https://github.com/rauenzi/trilium-types) ![trilium-types](https://img.shields.io/github/last-commit/rauenzi/trilium-types)
  A TypeScript `@types` package for Trilium Notes.

---

## 📚 Wikis & documents

* [official wiki](https://github.com/zadam/trilium/wiki)
  The official wiki of trilium.
* [Chinese wiki](https://github.com/baddate/trilium-wiki)
  A Chinese translation of the official wiki.

---

## 🌐 Translation

Third-party translation for Trilium Notes.

* [trilium-translation](https://github.com/Nriver/trilium-translation) ![trilium-translation](https://img.shields.io/github/last-commit/Nriver/trilium-translation)
  The unofficial translation project for Trilium. For now, a Chinese translation is completed.

## 🔥 Contribution

You are welcome to fork and contribute to this repo.

The [Table of Contents](#table-of-contents) part is generated
by [https://github.com/ekalinin/github-markdown-toc](https://github.com/ekalinin/github-markdown-toc). Then reformatted
by `Ctrl + Alt + L` in PyCharm.
