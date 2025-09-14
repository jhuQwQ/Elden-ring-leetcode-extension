# Elden Ring LeetCode Extension

Enhance your LeetCode experience with Elden Ring–inspired notifications and achievements.

![Demo](demo-image.png)

## Installation

1. Clone this repository
2. Install dependencies:

   ```bash
   npm install
   ```
3. Build the extension:

   ```bash
   npm run build
   ```

## Loading the Extension

### For Zen Browser (Recommended)

1. Open Zen Browser and navigate to `about:debugging`
2. Click **This Firefox** (or **This Zen Browser**)
3. Click **Load Temporary Add-on...**
4. Navigate to the `dist` directory and select `manifest.json`
5. The extension will be loaded temporarily until you restart Zen Browser

**Note**: This extension has been converted to Firefox WebExtension format for compatibility with Zen Browser, which is based on Firefox.

### For Chrome/Chromium-based browsers

If you prefer to use Chrome, you'll need the original Chrome version:
1. Open Chrome and navigate to `chrome://extensions/`
2. Enable **Developer mode** (top-right toggle)
3. Click **Load unpacked**
4. Select the `dist` directory from this project

### Permanent Installation

For permanent installation in Zen Browser, you would need to:
1. Package the extension as a `.xpi` file
2. Install it through Firefox Add-ons or load it via `about:addons`

## Features

* Elden Ring–styled notifications for LeetCode submissions
* Achievement system for coding milestones
* Immersive, game-inspired UI elements

## Contributing

Contributions are welcome. Please submit issues or enhancement requests.

## Credits

Inspired by [this X post](https://x.com/saltyAom/status/1966608243167555734).
