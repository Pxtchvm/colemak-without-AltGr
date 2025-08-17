# Colemak Without AltGr

Vanilla Colemak keyboard layout (Capslock as Backspace) for Windows without AltGr functionality.

## Features

- Standard Colemak layout
- No AltGr keys (So pressing Ctrl + Alt doesn't ruin your keyboard shortcuts)
- Simple installer for Windows (x86, x64, ia64)

---

## Quick Start

1. **Run the Setup**

   - Go to the `setup/` folder.
   - Double-click `setup.exe`.
   - If the window closes without a success message, please wait—it may take longer than expected.
   - **Restart your computer** after installation.

2. **Switch to the Layout**
   - Open Windows `Language preferences`.
   - Add/select the new Colemak layout.
   - Use `Win + Space` to switch between layouts.

---

## Building from Source

1. Install [Microsoft Keyboard Layout Creator (MSKLC)](https://www.microsoft.com/en-us/download/details.aspx?id=102134) and [.NET Framework v3.5](https://www.microsoft.com/en-ph/download/details.aspx?id=21).
2. Open the `.klc` file in MSKLC.
3. Use `Build DLL and Setup Package` in MSKLC.
4. For more help, see [Henri's MSKLC Guide](https://msklc-guide.github.io/).

---

## Troubleshooting & Uninstall

- If installation fails, ensure you have restarted your computer.
- To uninstall:
  1. Remove the layout from `Language preferences`.
  2. Go to `Settings > Apps & Features`, find the layout, and uninstall.
  3. Restart your computer.
- If you have issues with `.klc` files, ensure they use CRLF line endings and UTF-16LE-BOM encoding.

---

## Credits

- Based on resources from [DreymaR](https://github.com/DreymaR).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
