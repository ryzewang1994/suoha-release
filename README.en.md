<div align="center">

# 🎰 梭哈工具台 · Suoha Workbench

**本地原生 Windows 桌面效率工具箱 —— 把常用的小工具一次「梭哈」到一个窗口里，数据全部留在本机**

**A native Windows productivity toolbox — all your everyday little tools in one window, with every byte of data kept on your own PC**

![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D6?style=flat-square&logo=windows)
![Stack](https://img.shields.io/badge/Tauri%202-Rust%20%2B%20React-24C8DB?style=flat-square&logo=tauri)
![Size](https://img.shields.io/badge/Installer-~7%20MB-brightgreen?style=flat-square)
![i18n](https://img.shields.io/badge/UI-中文%20%7C%20English%20%7C%20Español-orange?style=flat-square)

[中文](#中文) · [English](#english)

</div>

---

## 中文

### 📥 下载安装

- 到本仓库的 **Releases（发行版）** 页面下载最新的 `suoha-workbench_<版本号>_x64-setup.exe`，双击安装即可。
- 安装到当前用户目录，**不需要管理员权限**；安装包约 7 MB。
- 支持 Windows 10（21H2 及以上）和 Windows 11，系统自带的 WebView2 即可运行。
- 程序会自动检查更新（自有服务器 → Gitee → GitHub 依次尝试），有新版本时提示一键升级。
- 安装时若杀毒软件提示风险：程序目前尚未购买代码签名证书，属于误报，可选择「仍要运行 / 信任」。

### ✨ 主要功能

| 模块 | 能做什么 |
|---|---|
| 📋 **超级剪贴板** | `Ctrl+Shift+V` 唤出：文字、图片、文件、Excel 表格、带格式文本都能收；固定、分组、搜索，Enter 原样粘贴、Tab 纯文本粘贴 |
| ✂️ **截图 / 贴图 / 长截图** | 框选截图并标注（箭头、马赛克、荧光笔、文字…），贴到桌面置顶；网页长截图配合浏览器扩展精确拼接 |
| 🎬 **录屏 / GIF** | 录制屏幕区域为视频或 GIF；鼠标聚光，点击有涟漪特效，左右键可区分 |
| 🔍 **聚合搜索** | 双击 `Ctrl` 呼出，一个框搜网址、工具、待办、剪贴板记录和本机文件 |
| ✅ **待办管家** | 四象限待办、链接 / 附件 / 求助人、逾期提醒、桌面便签 |
| 🔄 **闭环管理** | 长线事项跟踪：背景、进展时间线、里程碑、闭环结论，一键导出回溯 |
| 📅 **排班管理** | 按团队 / 项目排班，合同约束与自动预警，工时汇总与图表，导出 Excel |
| 📡 **局域网互传** | 同一局域网自动发现，定向发送文件、文件夹、待办、排班；对方确认才接收，端到端加密，不经服务器 |
| 🧭 **网址导航** | 分类书签、自定义搜索引擎、批量添加与分享 |
| 🎓 **记忆大师** | 自建词典与知识点，悬浮卡片定时滚动记忆，AI 生成导入 |
| 🛠️ **工具工坊** | 图表绘制、邮件设计、时区时钟、汇率、JSON、正则、二维码、密码管理等数十个小工具 |
| 🧠 **记忆长廊** | 剪贴板自动归档，按日历浏览、全文搜索 |
| 🌐 **多语言** | 内置中文、English、Español，可用 AI 一键生成其他语言 |

### 🔒 隐私

- 所有数据存放在本机（`~/.suoha-console/`），不上传任何服务器。
- 局域网互传只在局域网内点对点加密传输。
- AI 功能需要你自己填写所用服务的密钥，请求直接从本机发往你选择的服务。

### 📝 更新记录

每个版本的变化见 [Releases](../../releases) 页面，程序内「检查更新」也会显示。

---

## English

### 📥 Download & Install

- Grab the latest `suoha-workbench_<version>_x64-setup.exe` from this repository's **Releases** page and double-click to install.
- Installs per user — **no administrator rights needed**; the installer is about 7 MB.
- Runs on Windows 10 (21H2 or later) and Windows 11 using the built-in WebView2.
- Updates are checked automatically (own server → Gitee → GitHub, in that order) and installed with one click.
- If your antivirus warns during install: the app is not code-signed yet, so this is a false positive — choose "Run anyway / Trust".

### ✨ Features

| Module | What it does |
|---|---|
| 📋 **Super Clipboard** | Press `Ctrl+Shift+V`: keeps text, images, files, Excel tables and rich text; pin, group, search; Enter pastes as-is, Tab pastes plain text |
| ✂️ **Screenshot / Pin / Scrolling capture** | Region capture with annotations (arrows, mosaic, highlighter, text…), pin to the desktop; precise full-page web captures with the browser extension |
| 🎬 **Screen recording / GIF** | Record a region to video or GIF; cursor spotlight with click ripples that tell left and right clicks apart |
| 🔍 **Quick Search** | Double-tap `Ctrl` to search bookmarks, tools, todos, clipboard history and local files from one box |
| ✅ **Todos** | Eisenhower-matrix todos with links, attachments, helpers, overdue reminders and desktop sticky notes |
| 🔄 **Close-the-Loop** | Track long-running matters: background, progress timeline, milestones, conclusion, one-click export |
| 📅 **Shift Scheduling** | Team / project rosters with contract rules, automatic warnings, hour summaries, charts and Excel export |
| 📡 **LAN Transfer** | Auto-discovers peers on your LAN; send files, folders, todos or rosters to a chosen person; receiver must accept; end-to-end encrypted, no server involved |
| 🧭 **Bookmarks** | Categorised links, custom search engines, bulk add and sharing |
| 🎓 **Memory Master** | Your own vocabulary and knowledge cards, floating flash cards, AI-assisted import |
| 🛠️ **Workshop** | Dozens of tools: chart maker, email designer, world clock, currency, JSON, regex, QR codes, password manager and more |
| 🧠 **Memory Gallery** | Automatic clipboard archive, browse by calendar, full-text search |
| 🌐 **Languages** | Chinese, English and Español built in; generate any other language with AI in one click |

### 🔒 Privacy

- All data stays on your PC (`~/.suoha-console/`); nothing is uploaded.
- LAN Transfer is peer-to-peer and encrypted, inside your local network only.
- AI features use your own API key; requests go straight from your PC to the service you choose.

### 📝 Changelog

See the [Releases](../../releases) page for what changed in each version; the in-app "Check for updates" shows it too.
