# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-file offline text editor built with vanilla HTML, CSS, and JavaScript. The entire application is contained in `index.html` with no external dependencies.

## Architecture

- **Single HTML file**: `index.html` contains the complete application
- **Inline CSS**: All styles are embedded in the `<style>` section
- **Vanilla JavaScript**: Uses plain JavaScript with localStorage for persistence
- **ContentEditable**: The editor uses a `contenteditable` div for text input
- **LocalStorage persistence**: Content and formatting preferences are auto-saved using localStorage with abbreviated keys (`c`, `ff`, `fs`, `fc`)

## Key Components

- **Editor window**: Styled container with title bar and toolbar
- **Toolbar**: Contains font family, size, color controls and action buttons
- **Content area**: ContentEditable div where users type
- **Code snippet functionality**: Allows inserting styled code blocks
- **Print support**: CSS media queries hide UI elements when printing

## Development Notes

- No build process or package.json - this is a standalone HTML file
- Testing should be done by opening `index.html` directly in browsers
- The minified JavaScript uses closure pattern `!function(l){}({})` where `l` represents localStorage
- Font settings and content are persisted automatically on change
- Print styles are handled via CSS media queries, not JavaScript