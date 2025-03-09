# Offline Text Editor

A lightweight, customizable text editor that works entirely in your browser without requiring server connections.

## Features

-   **Fully Offline** - Works without internet connection
-   **Persistent Storage** - Automatically saves content and formatting preferences in your browser
-   **Close/Refresh Warning** - Confirms before closing or refreshing to prevent accidental navigation
-   **Font Customization** - Change font family, size, and color to suit your preferences
-   **Code Snippets** - Insert and format code with proper styling
-   **Undo/Redo Support** - Use Ctrl+Z and Ctrl+Y for standard text editing operations
-   **Minimalist Design** - Clean, distraction-free writing environment
-   **Lightweight** - Single HTML file, no dependencies
-   **Responsive** - Works on mobile and desktop devices

## How It Works

This text editor is built with plain HTML, CSS, and JavaScript. It uses the browser's localStorage to automatically save your content and formatting preferences as you type, ensuring you never lose your work even if you close the tab or browser.

## Usage

### Option 1: Direct Download

1. Download the `index.html` file
2. Open it in any web browser
3. Start typing!

### Option 2: One-Line Installation

Copy and paste this command in your terminal:

```bash
curl -o offline-editor.html https://raw.githubusercontent.com/rohandhamapurkar/offline-text-editor/main/index.html
```

### Option 3: Online Version

Access the editor directly at [https://rohandhamapurkar.github.io/temp-editor/](https://rohandhamapurkar.github.io/temp-editor/)

## Text Formatting Options

-   **Font Family** - Choose from various fonts including monospace, serif, sans-serif, and more
-   **Font Size** - Select from small, medium, large, x-large, and xx-large options
-   **Text Color** - Pick any color using the color picker
-   **Code Snippets** - Format selected text as code or insert an empty code block

## Keyboard Shortcuts

-   **Ctrl+Z** - Undo last action
-   **Ctrl+Y** (or **Ctrl+Shift+Z** depending on browser) - Redo last undone action

## Technology

-   **HTML5** - Structure
-   **CSS3** - Styling
-   **Vanilla JavaScript** - Functionality
-   **LocalStorage API** - Persistent data storage

## Customization

You can easily customize the editor further by modifying the CSS in the `<style>` section:

-   Change the default fonts by updating the options in the font-family dropdown
-   Modify code snippet styling by adjusting the `.code-snippet` class properties
-   Adjust the toolbar layout with the flexbox properties in the `.toolbar` class

## Browser Compatibility

-   Chrome (latest)
-   Firefox (latest)
-   Safari (latest)
-   Edge (latest)
-   Opera (latest)

## License

MIT License - Feel free to use, modify, and distribute as you wish.

## Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Future Enhancements

-   Export to PDF/TXT
-   Markdown support
-   Additional text formatting options (bold, italic, underline)
-   Dark mode toggle
-   Word count
-   Syntax highlighting for code snippets
-   Custom themes

---

Created with ❤️ by Rohan Dhamapurkar
