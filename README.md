# Sayvia

A powerful macOS translation tool that allows you to translate selected text instantly with keyboard shortcuts.

## Features

- 🚀 **Instant Translation**: Select any text and press ⌘D to translate
- 🎯 **Smart Text Selection**: Multiple fallback methods ensure text capture works in any app
- 🌐 **Multi-Language Support**: Translate between Chinese, English, and more
- 🔒 **Privacy First**: All text processing happens locally, only translation requests are sent to the API
- ⚡ **Fast & Lightweight**: Runs in the menu bar, minimal resource usage

## System Requirements

- macOS 15.0 or later
- Apple Silicon (M1/M2/M3) or Intel Mac

## Installation

1. Download the latest `Sayvia-x.x.x.dmg` from [Releases](https://github.com/maomao000211/TalkBridge-Release/releases)
2. Open the DMG file
3. Drag Sayvia to the Applications folder
4. Launch TalkBridge from Applications
5. Grant required permissions when prompted:
   - **Accessibility**: Required to read selected text from other apps
   - **Automation**: Required to simulate keyboard shortcuts for text copying

## Usage

### Keyboard Shortcuts

- **⌘D**: Translate selected text
- **⌘⇧C**: Translate clipboard content
- **⌘⇧V**: Open translation input window

### First Time Setup

1. Launch Sayvia - it will appear in your menu bar
2. Click the menu bar icon and select "Settings"
3. Configure your preferred translation settings
4. Grant permissions when prompted

### Translating Text

1. Select any text in any application
2. Press **⌘D**
3. Translation will appear in a popup window near your cursor

## Permissions Explained

### Accessibility Permission
Sayvia needs accessibility permission to read selected text from other applications. This is the core functionality that enables instant translation.

**What we access**: Only the text you have selected
**What we don't access**: Passwords, system data, or any other content

### Automation Permission
Sayvia uses automation to simulate the Cmd+C keyboard shortcut as a fallback method when direct text selection is not available.

**What we do**: Simulate Cmd+C to copy selected text
**What we don't do**: Control other apps or execute commands

## Privacy & Security

- ✅ **Local Processing**: Text selection and clipboard operations are processed locally on your Mac
- ✅ **Secure Storage**: Settings are stored locally, API keys are stored in macOS Keychain
- ✅ **Minimal Network**: Only translation requests are sent to the translation API
- ✅ **No Analytics**: We do not collect any usage data or analytics
- ✅ **Open Source**: Core code is available for review (private repository)

## Troubleshooting

### Translation not working
1. Check that Accessibility permission is granted in System Settings > Privacy & Security > Accessibility
2. Try removing and re-adding TalkBridge in the Accessibility list
3. Restart the application

### "No text selected" error
1. Make sure you have actually selected text before pressing ⌘D
2. Try using ⌘⇧C to translate clipboard content instead
3. Some apps may have limited accessibility support - try the clipboard method

### App won't open
1. Right-click the app and select "Open" (first time only)
2. Check System Settings > Privacy & Security for any blocks

## Support

If you encounter any issues or have questions:
- Open an issue on [GitHub](https://github.com/maomao000211/TalkBridge-Release/issues)
- Email: maoglobal.211@gmail.com

## Version History

### v1.0.1 (2026-05-11)
- Fixed accessibility permission persistence issue
- Improved text selection reliability in WhatsApp and other apps
- Added Developer ID signing and notarization
- Enhanced privacy information in About page

### v1.0.0 (2026-05-10)
- Initial release
- Core translation functionality
- Multi-tier text selection strategy
- Menu bar interface

## License

Copyright © 2024 TalkBridge. All rights reserved.

---

Made with ❤️ for macOS users who need instant translation
