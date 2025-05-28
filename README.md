# Harajuku Shell - Advanced Web Shell

## 🚀 Overview

Harajuku Shell is an advanced web shell with a modern interface designed for easy and efficient server management. Equipped with elegant Black Gold & Red Gold themes and various advanced features for system administration.

## ✨ Features

### 🎨 Modern Interface
- **Black Gold & Red Gold Theme** - Modern design with elegant gold and red colors
- **Matrix Rain Background** - Animated matrix background effect with golden colors
- **Responsive Design** - Optimal display on all devices
- **Smooth Animations** - Smooth animations and attractive transitions

### 📁 File Management
- **File Browser** - Browse directories with ease
- **File Editor** - Edit files directly from browser
- **File Upload** - Upload multiple files at once
- **File Creation** - Create new files with various extensions
- **Permission Management** - Change file and directory permissions
- **Rename & Delete** - Manage files and folders easily

### 💻 Terminal Features
- **Command Execution** - Run system commands with clean output
- **Command Suggestions** - Quick command buttons for convenience
- **Enhanced Output** - Terminal output cleaning from control characters
- **Copy Functionality** - Copy terminal output easily
- **Interactive Warnings** - Warnings for potentially problematic commands

### 🔐 Security Features
- **Password Authentication** - Secure authentication system
- **Ultra Safe Mode** - Safe mode to prevent HTTP 500 errors
- **Progressive Loading** - Progressive loading for stability
- **Error Handling** - Comprehensive error handling
- **Session Management** - Secure session management

## 🛠️ Installation

1. **Upload File**
   ```bash
   # Upload harajuku.php to your server
   ```

2. **Set Permissions**
   ```bash
   chmod 644 harajuku.php
   ```

3. **Access Shell**
   ```
   http://yourserver.com/harajuku.php
   ```

4. **Login**
   - Default password: `haitogensou123`
   - Change password in the file for security

## 📋 Usage

### File Manager
1. Click **File Manager** to browse files
2. Click file name to view contents
3. Use **Edit** button to edit files
4. Use **Actions** for other file operations

### Command Terminal
1. Click **Command** to open terminal
2. Use **Quick Commands** for common commands
3. Type manual commands in input field
4. Click **Execute** to run

### File Upload
1. Click **Upload** in menu
2. Select files to upload
3. Click **Upload Files**
4. Files will be saved in current directory

### Create Files
1. Click **Create File** in menu
2. Enter file name and select extension
3. Write file content
4. Click **Create File**

## ⚙️ Configuration

### Change Password
Edit `harajuku.php` file and change the line:
```php
$password = "haitogensou123";
```

### Customize Theme
Change CSS variables in the `:root` section to customize colors:
```css
:root {
    --primary-color: #ffd700;
    --secondary-color: #ffb347;
    --accent-color: #dc143c;
}
```

## 🎯 Keyboard Shortcuts

- **Ctrl + /** - Focus to command input
- **Ctrl + S** - Save file (in edit mode)
- **Escape** - Clear focus from active element

## 🔧 Troubleshooting

### Commands Not Working
- Check if function execution is allowed on server
- Try using alternative commands
- Check directory permissions

### File Upload Failed
- Check upload directory permissions
- Ensure file size doesn't exceed server limit
- Check available disk space

### Error 500
- Enable debug mode by adding `?debug=1` to URL
- Check server error logs
- Ensure PHP version compatibility

## 📊 Supported File Types

### Text Files
- PHP, HTML, CSS, JavaScript
- Python, Shell Script, SQL
- XML, JSON, YAML, Markdown
- Plain text files

### Operations
- View, Edit, Delete, Rename
- Change permissions (chmod)
- Download, Upload
- Create new files

## 🛡️ Security Notes

1. **Change Default Password** - Always change the default password
2. **Secure Location** - Store in a location that's not easily guessable
3. **Regular Updates** - Update regularly
4. **Monitor Access** - Monitor shell access
5. **Remove After Use** - Delete after finished using

## 📱 Browser Compatibility

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🎨 Theme Customization

The shell uses CSS custom properties that are easy to customize:

```css
/* Primary colors */
--primary-color: #ffd700;    /* Gold */
--secondary-color: #ffb347;  /* Light orange */
--accent-color: #dc143c;     /* Crimson */

/* Background colors */
--primary-bg: #0a0a0a;       /* Dark black */
--secondary-bg: #1a1a1a;     /* Dark gray */
--accent-bg: #2a2a2a;        /* Medium gray */
```

## 🚀 Advanced Features

### Enhanced Terminal
- Smart command suggestions with quick buttons
- ANSI escape sequence cleaning for better output
- Copy functionality for command results
- Interactive command warnings for problematic commands

### Modern UI/UX
- Gradient animations and smooth transitions
- Matrix rain background effect
- Responsive grid layout
- Professional color scheme

### File Operations
- Batch file upload with progress indication
- Inline file editing with syntax awareness
- Advanced permission management
- Directory creation and navigation

## 📄 License

This project is for educational purposes only. Use responsibly and only on systems you own or have permission to access.

## ⚠️ Disclaimer

- Use only on servers you own or have permission to access
- Unauthorized use may violate laws
- Always follow security best practices
- Author is not responsible for misuse

---

**🔒 Security First**: Always prioritize security and use this shell wisely. 