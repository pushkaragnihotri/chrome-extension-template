# Chrome Extension Template (Manifest V3)

A clean starter template for building Chrome extensions.

## Features

- Manifest V3
- Popup UI
- Background service worker
- Content script ready
- Simple, minimal structure

## Structure

```css
├── manifest.json
├── background.js
├── scripts/
│   ├── content.js
│   └── react.production.min.js
├── popup/
│   ├── popup.html
│   ├── popup.js
│   └── popup.css
└── images/
    ├── icon-16.png
    ├── icon-32.png
    ├── icon-48.png
    └── icon-128.png
```

### Where will be different sized images displayed?

1. 16x16 - Favicon on the extension's pages and context menu.
2. 32x32 - Windows computers often require this size.
3. 48x48 - Displays on the Extensions page.
4. 128x128 - Displays on installation and in the Chrome Web Store.

## Usage

1. Click **Use this template**
2. Clone your new repo
3. Load it in Chrome:
   - Go to `chrome://extensions`
   - Enable **Developer mode**
   - Click **Load unpacked**
   - Select the project folder

## Customize

- Edit `manifest.json`
- Update popup UI
- Add permissions as needed

Happy building 🚀
