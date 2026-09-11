# Omoi & Azuki Chapter Downloader

A Tampermonkey userscript designed to seamlessly extract, convert, and download high-quality manga chapters from Omoi.com and Azuki.co. 

## ✨ Core Features

* **Smart API Interception:** Silently monitors background network traffic to capture the site's v1 API data, ensuring pages are downloaded in the exact correct reading order.
* **WebP to PNG Conversion:** Automatically processes and converts native WebP image blobs into universally compatible, high-quality PNG files before saving.
* **Flat ZIP Architecture:** Packages all converted images directly into the root of a ZIP file—no annoying nested folders to dig through.
* **Live Status Panel:** Features a floating bottom-right UI that tracks scanned pages, monitors network requests, and updates download readiness in real-time.

## 🚀 Installation & Usage

1. **Prerequisite:** Install the **Tampermonkey** extension in your browser.
2. **Install Script:** Add the userscript via my Greasyfork profile.
3. **Load Chapter:** Open the chapter you wish to read on Omoi or Azuki.
4. **Scroll to End (CRITICAL):** You **must** scroll or slide all the way to the very bottom of the chapter. The script relies on performance observers to capture image URLs as they load on your screen.
5. **Download:** Once the floating panel turns green and says "Ready to download!", click the button to generate and save your ZIP archive.

## ⚠️ Disclaimer

**This script is strictly for educational purposes.** Please support the original creators and publishers. Do not repost, re-upload, or distribute the downloaded images.

## 🔗 Links, Feedback & Support

* **Greasyfork Scripts:** [ozler365's Profile](https://greasyfork.org/en/users/1553223-ozler365)
* **GitHub Repositories:** [ozler-s-works-info](https://ozler365.github.io/ozler-s-works-info/#/repositories)
* **Support the Developer:** Keep this script updated and running smoothly by leaving a small donation at [Buy Me a Coffee (ozler)](https://buymeacoffee.com/ozler).

For bug reports, feature requests, or general queries, please leave a review on Greasyfork or email **devjk6918@gmail.com**.
