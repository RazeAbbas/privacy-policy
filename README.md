# Privacy Policy for ChatGPT Presentation Mode

**Last updated:** February 2025

## Overview

ChatGPT Presentation Mode is a Chrome extension that modifies the display of chatgpt.com to provide a clean, distraction-free view for presentations, classrooms, and screen sharing.

## Data We Collect

**We do not collect, transmit, or store any personal data.**

The extension stores only local preferences on your device:

- **Presentation mode on/off** — whether the clean view is enabled
- **Dark mode preference** — your theme choice (light or dark)

This data is stored locally in your browser using Chrome's `storage.local` API. It never leaves your device.

## Permissions Explained

| Permission                | Why We Need It                                                           |
| ------------------------- | ------------------------------------------------------------------------ |
| `activeTab`             | To apply presentation mode when you click the extension on a ChatGPT tab |
| `scripting`             | To inject the presentation view logic into chatgpt.com                   |
| `storage`               | To remember your on/off and dark mode preferences                        |
| `tabs`                  | To check if the current tab is chatgpt.com before sending commands       |
| `https://chatgpt.com/*` | The extension only runs on ChatGPT. We do not access any other sites.    |

## Third-Party Services

We do not use analytics, tracking, or any third-party services. The extension does not communicate with any server except chatgpt.com (which you are already visiting).

## Contact

If you have questions about this privacy policy, please open an issue on the extension's GitHub repository or contact the developer through the Chrome Web Store listing.
