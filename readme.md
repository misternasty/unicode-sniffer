## Unicode Character Replacer
A lightweight, portable browser tool for detecting and replacing problematic Unicode characters in text.

(/img.png)

### Overview
Unicode Character Replacer helps writers, editors, and developers identify and normalize problematic Unicode characters that often sneak into text - such as zero-width spaces, various quote styles, and non-standard whitespace characters.

This tool runs entirely in your browser with no external dependencies, making it ideal for working with sensitive content without needing to transmit text to external servers.

### Features
* Character Detection: Identifies and counts special Unicode characters in your text
* Character Replacement: Normalizes text by replacing problematic characters with standard alternatives
* Custom Replacement Dictionary: Define and save your own character replacement rules
* Text Analysis: View detailed information about special characters in your text
* Export Options: Copy to clipboard or download processed text
* Local Storage: Save your replacement dictionary between sessions

Built-in Presets:
* Quotes Normalization: Converts typographic quotes (", ", ', ') to standard quotes (" and ')
* Space Characters: Normalizes various Unicode space types to standard spaces
* Dash/Hyphen Characters: Converts em dashes, en dashes, etc. to standard hyphens
* Zero-Width Characters: Removes invisible zero-width characters that cause issues

### Installation
This tool requires no installation. You have two options to use it:

##### Option 1: Use the online version
Visit https://your-username.github.io/unicode-character-replacer

##### Option 2: Run locally
Clone this repository:
```bash
git clone https://github.com/your-username/unicode-character-replacer.git
```
Open index.html in any modern web browser

### How to Use
Paste Text: Copy and paste your text into the "Input Text" area

### Configure Replacements:
Use the presets (quotes, spaces, dashes, zero-width) or
Add custom replacements by entering characters and their replacements

### Process Text:
Click "Process Text" to replace characters according to your rules
Click "Analyze Only" to see what characters are present without changing them

### Export Results: Copy to clipboard or download the processed text


### Example Use Cases
eBook Preparation: Clean up text that was converted from PDF before publishing
Code Debugging: Find invisible characters causing syntax errors
Content Management: Normalize text from various sources before adding to a database
Translation Work: Standardize quotation marks and other typography when translating between languages
Academic Papers: Ensure consistent typography when combining text from different sources

### Technical Details
Built with vanilla JavaScript, HTML, and CSS
Runs entirely client-side; no server component
Uses browser's localStorage API to persist settings
Unicode character detection and replacement via JavaScript regex

### License
This project is licensed under the MIT License - see the LICENSE file for details.
