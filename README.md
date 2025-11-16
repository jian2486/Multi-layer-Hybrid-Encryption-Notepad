# Secure Data Manager

A secure text storage application with encryption and customizable UI for Windows.

![Secure Data Manager UI](screenshot.png)

## Features

- **Strong Encryption**: Uses multiple AES encryption modes (CBC, CFB, OFB) with PBKDF2 key derivation
- **Data Obfuscation**: Custom encoding to make stored data less recognizable
- **Auto-save**: Automatically saves your data every 30 seconds
- **Customizable UI**: 
  - Adjustable colors for background, text, menus, title bar, and scrollbars
  - Multiple scrollbar styles (thin, wide, gray)
  - Multiple cursor styles (line, block, ibeam)
  - Transparency settings
  - Optional blur effect
- **Custom Window Decorations**: Custom title bar with minimize, maximize, and close buttons
- **Resizable Window**: Drag edges to resize the window
- **Configuration Persistence**: UI settings are saved and restored between sessions

## Installation

1. Download the latest release from the [Releases](https://example.com) page
2. Extract the archive to a folder of your choice
3. Run `secure_data_manager.exe`

**Note**: This application requires administrator privileges to run properly on Windows systems.

## Usage

1. Launch the application (may require administrator privileges)
2. Type or paste your sensitive information in the text area
3. The application automatically saves your data to `data.store` every 30 seconds
4. Use the "Theme" menu to customize the appearance
5. Close the application using the × button in the custom title bar

Data is automatically loaded from `data.store` on startup.

## Security Notes

- Data is encrypted using multiple AES modes with a hardcoded key for demonstration
- Data is stored in the `data.store` file in the same directory as the application
- The application uses administrator privileges to ensure proper operation on Windows systems
- For maximum security, keep the `data.store` file in a secure location

## Customization

The application allows extensive UI customization:
- Background and text colors
- Menu colors
- Title bar colors
- Scrollbar colors and styles
- Cursor colors and styles
- Window transparency
- Optional background blur effect

All settings are saved and restored automatically.

## File Structure

- `secure_data_manager.exe` - Main application executable
- `data.store` - Encrypted data storage file (created after first save)
- `README.md` - This file

## Source Code

The source code is not publicly available. If you're interested in the implementation details or would like to contribute, please contact the project maintainers.

## License

This project is provided for educational purposes. Use at your own risk.