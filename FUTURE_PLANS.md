# Future Plans for Naruto Editor

This document outlines the roadmap for the Naruto Editor project. Phase 1 focused on establishing the base UI and integrating the editor libraries. Phase 2 and beyond will focus on adding functionality and improving the user experience.

## Phase 1: Foundation (Completed)

*   [x] Basic UI layout using CSS Grid.
*   [x] Integration of CodeMirror for text editing.
*   [x] Integration of Ace Editor as an alternative.
*   [x] Custom window title bar and controls styling.
*   [x] File explorer UI with resizable pane.
*   [x] Basic documentation and code comments.

## Phase 2: Functionality & Interactivity (Proposed)

### 1. File System Integration
*   **Feature**: Allow users to actually open, save, and edit files from their local machine.
*   **Implementation**: Use the File System Access API (e.g., `window.showOpenFilePicker()`).

### 2. Enhanced Tab Management
*   **Feature**: Support multiple open tabs with state management.
*   **Implementation**:
    *   Clicking a file in the explorer opens a new tab.
    *   Switching tabs updates the editor content.
    *   Close buttons on tabs to remove them.

### 3. File Explorer Logic
*   **Feature**: Make the file explorer functional.
*   **Implementation**:
    *   Expand/collapse folder logic.
    *   Dynamic population of file tree based on an open directory.
    *   File icons based on extension (integrate `vscode-icons` or similar).

### 4. Settings & Preferences
*   **Feature**: Allow users to customize the editor.
*   **Implementation**:
    *   Settings modal or side panel.
    *   Change themes (Dracula, Monokai, Solarized, etc.).
    *   Font size, tab size, and line wrapping toggles.
    *   Persist settings using `localStorage`.

### 5. Terminal Integration
*   **Feature**: Add a built-in terminal.
*   **Implementation**: Use `xterm.js` to simulate a terminal in the bottom panel.

### 6. Code Execution
*   **Feature**: Run code directly in the browser.
*   **Implementation**:
    *   For JavaScript: `eval()` or a sandboxed iframe.
    *   For other languages: Integrate with an online compiler API (e.g., Judge0).

## Phase 3: Advanced Features

*   **Plugin System**: Allow external extensions.
*   **Git Integration**: Show git status in the file explorer and allow basic commits.
*   **IntelliSense/Autocompletion**: Enhanced language support using Language Server Protocol (LSP).
*   **Search**: Global search and replace across files.
