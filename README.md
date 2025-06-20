# Tampermonkey Script: Video Downloader for Dynamic Web Interfaces (e.g., Gemini UI)

This Tampermonkey user script enhances your web Browse experience by providing a convenient way to download video content from pages, particularly those with dynamically loaded media, such as certain generative AI interfaces like Gemini.

## 🚀 Features

* **One-Click Download:** Adds a persistent "Download All Videos" button to the bottom-right corner of any webpage.

* **Automatic Video Detection:** Scans the page for all `<video>` elements.

* **Intelligent Filenaming:** Attempts to derive a sensible filename from the video's URL, including checking for `filename` query parameters or path segments. Falls back to a unique timestamped name if no clear filename is found.

* **Non-Intrusive:** The script only adds a button and does not interfere with the page's existing functionality until the button is clicked.

* **User Feedback:** Provides small, temporary on-screen messages to indicate the script's status (e.g., "button added," "downloads initiated," "no videos found").

## 🛠️ Installation

1.  **Install Tampermonkey:** If you don't already have it, install the Tampermonkey browser extension for your preferred browser:
    * [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    * [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
    * [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpbldcldlgbcehfjdfdfjfmjgp)
    * (and other browsers supported by Tampermonkey)

2.  **Create a New Script:**
    * Click on the Tampermonkey icon in your browser's toolbar.
    * Select "Create a new script..." or go to "Dashboard" and click the `+` icon.

3.  **Paste the Code:**
    * Copy the entire script content from the `tampermonkey-gemini-video-downloader` immersive previously shared.
    * Paste the copied code into the Tampermonkey editor, replacing any default "Hello World" code.

4.  **Save the Script:**
    * Go to "File" > "Save" in the Tampermonkey editor, or use the keyboard shortcut (`Ctrl+S` or `Cmd+S`).

## 💡 Usage

1.  **Navigate to a Page:** Go to any webpage that contains video elements, such as the Gemini user interface where videos are displayed.

2.  **Click the Button:** Once the page has loaded, you'll see a floating "Download All Videos" button with a download icon at the bottom-right corner of your browser window.

3.  **Initiate Download:** Click this button. The script will then attempt to download all detected video files.

4.  **Check Downloads:** Your browser's download manager will show the progress of the video downloads.

## ⚠️ Disclaimer

This script is provided as-is for personal use and convenience. It is an independent creation and has **no affiliation with, endorsement by, or official connection to Google, Gemini, or any of their products or services.** Use of this script should comply with the terms of service of the websites you visit. The author of this script is not responsible for its misuse.

# Tampermonkey 脚本：动态网页视频下载器（例如 Gemini UI）

**更新日期：2025年6月19日**

这个 Tampermonkey 用户脚本通过提供一种便捷的方式，让您可以从网页上下载视频内容，尤其适用于那些包含动态加载媒体的页面，例如某些生成式 AI 界面（如 Gemini），**特别针对下载 VOE3 模型生成的视频**。

## 🚀 功能特性

* **一键下载：** 在任何网页的右下角添加一个常驻的“下载所有视频”按钮。

* **自动视频检测：** 扫描页面中所有的 `<video>` 元素。

* **智能文件命名：** 尝试从视频的 URL 中获取一个合理的文件名，包括检查 `filename` 查询参数或路径片段。如果未找到清晰的文件名，则回退到使用唯一的带时间戳的名称。

* **非侵入性：** 脚本只添加一个按钮，在您点击按钮之前，不会干扰页面现有功能。

* **用户反馈：** 提供小而临时的屏幕消息，以指示脚本状态（例如，“按钮已添加”、“已开始下载”、“未找到视频”）。

## 🛠️ 安装方法

1.  **安装 Tampermonkey：** 如果您尚未安装，请为您偏好的浏览器安装 Tampermonkey 浏览器扩展：
    * [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    * [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
    * [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpbldcldlgbcehfjdfdfjfmjgp)
    * （以及 Tampermonkey 支持的其他浏览器）

2.  **创建新脚本：**
    * 点击浏览器工具栏中的 Tampermonkey 图标。
    * 选择“创建新脚本...”或前往“仪表板”并点击 `+` 图标。

3.  **粘贴代码：**
    * 从 AI 提供的 `tampermonkey-gemini-video-downloader` immersive 中复制整个脚本内容。
    * 将复制的代码粘贴到 Tampermonkey 编辑器中，替换任何默认的“Hello World”代码。

4.  **保存脚本：**
    * 在 Tampermonkey 编辑器中选择“文件”>“保存”，或使用键盘快捷键（`Ctrl+S` 或 `Cmd+S`）。

## 💡 使用方法

1.  **导航到页面：** 前往任何包含视频元素的网页，例如显示视频的 Gemini 用户界面。

2.  **点击按钮：** 页面加载完成后，您会在浏览器窗口的右下角看到一个带有下载图标的浮动“下载所有视频”按钮。

3.  **开始下载：** 点击此按钮。脚本将尝试下载所有检测到的视频文件。

4.  **检查下载：** 您的浏览器下载管理器将显示视频下载的进度。

## ⚠️ 免责声明

此脚本按原样提供，仅供个人使用和方便。它是一个独立创作，与 **Google、Gemini 或其任何产品或服务没有任何关联、认可或官方连接。** 使用此脚本应遵守您访问网站的服务条款。此脚本的作者不对其误用负责。
