# Code Formatter & Highlighter (Chrome Extension)

A lightweight, powerful Chrome Extension that auto-formats and syntax-highlights pasted code. It features a smart parser that can detect raw SQL embedded inside JSON strings and format both the JSON structure and the inner SQL beautifully.

## Features
* **Smart Nested Parsing:** Paste a JSON payload containing raw SQL strings, and the tool will automatically format the JSON and neatly indent the SQL using template literals.
* **Auto-Detection:** Automatically detects whether your clipboard contains JSON, SQL, or plain text.
* **Manual Override:** Allows you to manually force syntax highlighting for SQL, JSON, or JavaScript.
* **Dark Mode UI:** Built with Tailwind CSS for a sleek, modern, developer-friendly interface.
* **One-Click Copy:** Easily copy the beautifully formatted code back to your clipboard.

## Technologies Used
* HTML5, CSS3, JavaScript (Vanilla)
* [Tailwind CSS](https://tailwindcss.com/) (via CDN for UI styling)
* [Highlight.js](https://highlightjs.org/) (for syntax highlighting)
* [sql-formatter](https://github.com/sql-formatter-org/sql-formatter) (for parsing and formatting raw SQL)

## Local Installation (Developer Mode)

To run this extension locally on your machine without installing it from the Chrome Web Store:

1. Clone or download this repository to your local machine.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Turn on **Developer mode** using the toggle switch in the top right corner.
4. Click the **Load unpacked** button in the top left.
5. Select the directory where you cloned/downloaded this repository.
6. The extension is now installed! Click the puzzle piece icon 🧩 in your Chrome toolbar and pin 📌 the "Code Formatter & Highlighter" to access it easily.

## Publishing
To publish to the Chrome Web Store, compress the project files (`manifest.json`, `popup.html`, icons, etc.) into a `.zip` file. Do not include the root directory itself in the zip, just the contents. Upload this zip to the Chrome Developer Dashboard.

## License
MIT

*Note: See [AI_DISCLOSURE.md](AI_DISCLOSURE.md) for details on AI assistance in this project.*
