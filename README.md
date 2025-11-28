# Naruto Editor UI

UI Created for Naruto Editor using HTML, CSS and CodeMirror/Ace.

## Description

Naruto Editor is a web-based code editor UI demonstration. It provides a sleek, dark-themed interface resembling modern desktop IDEs like VS Code. This project primarily focuses on the frontend user interface, showcasing how to integrate powerful code editing libraries like CodeMirror and Ace Editor into a custom layout with features like:

*   **Window Management**: Custom title bar with minimize, maximize, and close buttons.
*   **File Explorer**: A resizable side panel to browse files and folders (UI only).
*   **Code Editor**: Syntax highlighting, line numbers, and theming provided by CodeMirror or Ace.
*   **Status Bar**: Information about the file and language.
*   **Menu Bar**: Dropdown menus for file and edit operations.

## Features

*   **Multiple Views**:
    *   `window.html`: A full-featured IDE layout with a file explorer and menu bar using CodeMirror.
    *   `single-file.html`: A simplified view focusing on a single file editor with a status bar.
    *   `window-ace.html`: An alternative implementation using Ace Editor instead of CodeMirror.
*   **Resizable Layout**: The file explorer pane can be resized (requires jQuery UI).
*   **Theming**: Uses the Dracula theme for CodeMirror and Monokai for Ace.
*   **Syntax Highlighting**: Configured for JavaScript.

## Technologies Used

*   **HTML5**: Structure of the application.
*   **CSS3**: Styling using CSS Grid and Flexbox for layout.
*   **JavaScript**: Logic for initializing editors and handling UI interactions.
*   **jQuery & jQuery UI**: Used for DOM manipulation and the resizable interaction.
*   **CodeMirror**: A versatile text editor implemented in JavaScript for the browser.
*   **Ace Editor**: A standalone code editor written in JavaScript.

## Getting Started

### Prerequisites

*   A modern web browser (Chrome, Firefox, Safari, Edge).
*   Internet connection (to load CDNs for jQuery and Ace Editor).

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/yourusername/naruto-editor-ui.git
    ```
2.  Navigate to the project directory:
    ```bash
    cd naruto-editor-ui
    ```

### Usage

Since this is a client-side only project, you can open the HTML files directly in your browser.

*   **Full Editor (CodeMirror)**: Open `window.html` in your browser.
*   **Single File Editor**: Open `single-file.html` in your browser.
*   **Ace Editor Version**: Open `window-ace.html` in your browser.

## Project Structure

```
.
├── css/
│   ├── single-file-styles.css  # Styles for the single file view
│   └── styles.css              # Main styles for the window view
├── editor/                     # Local copy of CodeMirror library
├── single-file.html            # Entry point for single file view
├── window.html                 # Entry point for full window view
├── window-ace.html             # Entry point for Ace editor view
└── README.md                   # Project documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[License Name] - see the LICENSE file for details.
