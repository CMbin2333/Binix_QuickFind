# Binix_QuickFind (BinixOvO) 🔍

A lightweight, highly responsive Chrome extension for comprehensive searching and managing of your bookmarks, browsing history, and downloads—all from a single, beautifully designed popup.

## ✨ Features

* **Unified & Categorized Search:** Seamlessly search across "Bookmarks", "History", "Downloads", or use the "Unified" tab to search everything at once.
* **Keyboard-Centric Navigation:** Say goodbye to the mouse. Use your keyboard to navigate through results, expand/collapse date groups, and perform actions.
* **Smart Date Grouping:** Results are automatically grouped and folded by date (e.g., Today, Yesterday, Weekdays) for a cleaner, organized view.
* **Bookmark Visit Tracking:** Automatically tracks how often you click your bookmarks and sorts them by visit frequency (customizable).
* **Quick Actions:** Hover over or select an item to quickly:
    * 📋 Copy URL
    * 📁 Open download folder
    * 🔄 Redownload canceled/interrupted files
    * 🗑️ Delete records (with a safety confirmation modal)
* **Dark Mode & Personalization:** Built-in Light and Dark modes. You can also customize the primary accent color to match your style.

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| `Ctrl + B` | Open the Binix_QuickFind popup |
| `↑` / `↓` | Navigate through search results |
| `←` / `→` | Collapse / Expand date groups |
| `Enter` | Open the selected item or toggle group expansion |
| `Del` | Delete the selected item |
| `Tab` | Switch between search categories |
| `Esc` | Close confirmation modals, settings, or the popup |

## 🚀 Installation

1. Clone or download this repository to your local machine.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer mode** in the top right corner.
4. Click on **Load unpacked** and select the folder containing the extension files (`manifest.json`, etc.).
5. Pin **BinixOvO** to your toolbar for quick access!

## 🔒 Privacy & Permissions

This extension runs entirely locally on your browser. It does not send any of your data to external servers.

* `bookmarks`: To search, read, and delete your bookmarks.
* `history`: To search and delete your browsing history.
* `downloads`: To search your downloaded files, open their folders, or retry failed downloads.
* `tabs`: To open search results in new tabs.
* `storage`: To save your extension settings, theme preferences, and bookmark visit statistics.

---
*Built with pure HTML, CSS, and Vanilla JavaScript. No bulky frameworks.*
