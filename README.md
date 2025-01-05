# My Editor Configuration

This repository contains my personal VS Code/Cursor editor configuration files, including settings, extensions, and keybindings.

## 🔧 Configuration Files

- `settings.json`: Main editor settings and preferences
- `extensions.json`: List of installed VS Code extensions
- `keybindings.json`: Custom keyboard shortcuts
- `syncLocalSettings.json`: Settings Sync configuration

## ⚙️ Key Features

### Theme & Visual Settings
- Theme: One Dark Pro Darker
- Font: JetBrains Mono Light with ligatures
- Material Icon Theme with React/Redux pack
- Custom GraphQL syntax highlighting

### Development Settings
- ESLint configuration for JavaScript/React
- Tailwind CSS support
- GraphQL support
- Playwright testing configuration
- Git integration with GitLens

### Code Quality & Format
- Format on save enabled
- ESLint auto-fix on save
- Semicolon removal in JavaScript/TypeScript
- Single quotes preference for JavaScript

### Performance Optimizations
- Large file optimizations enabled
- TypeScript server memory limit: 8096MB
- File watcher exclusions for common build directories
- Optimized workspace trust settings

## 🧩 Notable Extensions

1. **Code Quality & Style**
   - ESLint
   - Tailwind CSS IntelliSense
   - GraphQL

2. **Git & Collaboration**
   - GitLens
   - GitHub Pull Requests
   - Settings Sync

3. **Themes & Icons**
   - One Dark Pro
   - Material Icon Theme
   - A-File Icon

4. **AI & Productivity**
   - Cody AI
   - AWS CodeWhisperer
   - AWS Toolkit

5. **Testing & Development**
   - Playwright
   - Jupyter
   - Babel JavaScript

## 🔄 Sync Settings

Settings are synced using Settings Sync extension with the following configuration:
- Auto-upload enabled
- Auto-download enabled
- 20-second upload delay
- Workspace storage excluded from sync

## 💻 Terminal Configuration

- Default shell: zsh
- Font: MesloLGS NF
- Image support enabled
- Sticky scroll enabled
- Shell integration enabled

## 🎨 Custom Syntax Highlighting

Custom token colors for GraphQL:
- Type definitions: #e5c07b
- Variables and built-in types: Underlined

## 📝 Usage

1. Clone this repository
2. Copy the configuration files to your VS Code/Cursor user settings directory
3. Install the listed extensions
4. Restart your editor

## ⚠️ Note

Some settings might be specific to macOS. Adjust paths and settings according to your operating system and preferences. 