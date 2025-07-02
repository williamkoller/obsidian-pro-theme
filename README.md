# Obsidian Pro Theme for VS Code

A sleek and modern dark theme designed for professional developers. This theme features an ultra-dark interface with carefully selected accent colors that enhance code readability while maintaining a professional, minimalist aesthetic.

## 🌟 Features

- **Ultra Dark Interface**: Deep black backgrounds (#0a0a0a) for reduced eye strain
- **Minimal Sidebar**: Clean, distraction-free file explorer
- **Vibrant Syntax Highlighting**: Carefully chosen colors for optimal code readability
- **Professional Design**: Inspired by modern developer tools and productivity applications
- **High Contrast**: Perfect balance between dark backgrounds and bright syntax colors

## 🎨 Color Palette

### Interface Colors

- **Editor Background**: `#0a0a0a` - Ultra dark for focus
- **Sidebar**: `#070707` - Minimal and clean
- **Activity Bar**: `#050505` - Nearly black
- **Status Bar**: `#0f0f0f` - Subtle dark gray

### Syntax Colors

- **Keywords (const, let, var)**: `#8b5cf6` - Purple for declarations
- **Access Modifiers (public, private)**: `#3b82f6` - Blue for visibility
- **Functions**: `#22d3ee` - Cyan for function names and calls
- **Strings**: `#10b981` - Green for text literals
- **Numbers**: `#f59e0b` - Orange for numeric values
- **Classes/Types**: `#8b5cf6` - Purple for class definitions
- **Comments**: `#6b7280` - Muted gray for annotations
- **Variables**: `#e4e4e7` - Light gray for readability


## 🚀 Installation

### Method 1: Manual Installation

1. **Download the theme files**
2. **Open VS Code and navigate to the extensions folder:**

   - **Windows**: `%USERPROFILE%\.vscode\extensions`
   - **macOS**: `~/.vscode/extensions`
   - **Linux**: `~/.vscode/extensions`

3. **Create a new folder:**

   ```bash
   mkdir obsidian-pro-theme
   cd obsidian-pro-theme
   ```

4. **Create the required files:**

   **`package.json`**:

   ```json
   {
     "name": "obsidian-pro-theme",
     "displayName": "Obsidian Pro Theme",
     "description": "A sleek dark theme for professional developers",
     "version": "1.0.0",
     "publisher": "yourname",
     "engines": {
       "vscode": "^1.74.0"
     },
     "categories": ["Themes"],
     "keywords": [
       "theme",
       "dark",
       "obsidian",
       "modern",
       "minimal",
       "professional"
     ],
     "contributes": {
       "themes": [
         {
           "label": "Obsidian Pro",
           "uiTheme": "vs-dark",
           "path": "./themes/obsidian-pro-color-theme.json"
         }
       ]
     }
   }
   ```

5. **Create the themes folder and add the theme file**
6. **Restart VS Code**
7. **Activate the theme:**
   - Press `Ctrl+K Ctrl+T` (Windows/Linux) or `Cmd+K Cmd+T` (macOS)
   - Select **"Obsidian Pro"** from the list

### Method 2: From VS Code Marketplace

_Coming soon - theme will be published to the VS Code Marketplace_

## 🛠️ Customization

You can customize the theme by modifying the color values in the theme file. Common customizations include:

- **Adjusting background darkness**: Modify `editor.background` and `sideBar.background`
- **Changing keyword colors**: Update purple (`#8b5cf6`) for `const/let` and blue (`#3b82f6`) for `public/private`
- **Function highlighting**: Customize cyan (`#22d3ee`) values for functions
- **Syntax highlighting**: Customize individual token colors in the `tokenColors` section

## 🎯 Optimized For

- **TypeScript/JavaScript** development with enhanced keyword distinction
- **Object-oriented programming** with clear access modifier highlighting
- **React/Next.js** projects
- **Node.js** applications
- **Full-stack** development
- **Professional coding environments**

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the theme:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-improvement`)
3. Commit your changes (`git commit -m 'Add amazing improvement'`)
4. Push to the branch (`git push origin feature/amazing-improvement`)
5. Open a Pull Request

## 📝 Changelog

### Version 1.0.0

- Initial release
- Ultra-dark interface design
- Enhanced keyword highlighting with distinct colors:
  - Purple for `const`, `let`, `var` declarations
  - Blue for `public`, `private`, `static` modifiers
- Complete syntax highlighting for TypeScript/JavaScript
- Optimized color palette for code readability
- Minimal sidebar and activity bar styling


## 🙏 Acknowledgments

- Inspired by modern productivity applications and professional development tools
- Created for developers who appreciate clean, distraction-free coding environments
- Built with accessibility and eye strain reduction in mind
- Designed with enhanced keyword distinction for better code comprehension

---

**Enjoy coding with Obsidian Pro! 💎**

_If you like this theme, please consider giving it a ⭐ star and sharing it with your developer friends!_
