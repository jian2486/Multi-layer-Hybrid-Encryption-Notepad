# Secure Data Manager

A secure text storage application with encryption and customizable UI for Windows.
<img width="794" height="401" alt="image" src="https://github.com/user-attachments/assets/bedccfd8-c102-44e3-8350-0e3a47722e44" />
 - There is no need to pay attention to the Chinese settings.Just input directly.
 - Never close the program when decoding fails. Instead, terminate the program directly. Otherwise, the program will automatically save and overwrite the original content, and any possible information will be lost.😁

## Features

- **Strong Encryption**: Uses multiple AES encryption modes
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

## Security Notes

- Data is encrypted using multiple AES modes with a hardcoded key for demonstration
- Data is stored in the `data.store` file in the same directory as the application
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

## Source Code

The source code is not publicly available. If you're interested in the implementation details or would like to contribute, please contact the project maintainers.

## License

This project is provided for educational purposes. Use at your own risk.
