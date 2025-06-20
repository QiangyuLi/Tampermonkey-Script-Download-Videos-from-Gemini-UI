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
