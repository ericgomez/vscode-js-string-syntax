# JS String Syntax

**JS String Syntax** is a Visual Studio Code extension that highlights HTML and SQL embedded in JS strings. The extension automatically infers HTML and SQL content by default, while also supporting explicit language markers (`/*html*/` and `/*sql*/`) to identify and apply syntax highlighting to HTML content and SQL queries.

## Features

- **Automatic Language Detection**: Infers and highlights HTML and SQL content in JS strings without requiring explicit markers.
- **Explicit Language Markers**: Supports `/*html*/`, and `/*sql*/` comments for explicit language specification when needed.
- **Compatibility with Other Editors**: The use of language markers does not interfere with syntax in other editors or IDEs.
- **Multiple String Types**: Works with all JavaScript string types including single quotes (`'`), double quotes (`"`), and template literals (`` ` ``).

### Current Support

- **HTML** (auto-detected and with explicit marker)
- **SQL** (auto-detected and with explicit marker)

### Example

#### HTML Example

![html](./images/html_example.png)

#### SQL Example

![sql](./images/sql_example.png)

```js
const query = /*sql*/ `SET TRANSACTION ISOLATION LEVEL READ COMMITTED`;
```

Visual Studio Code will apply HTML, and SQL syntax highlighting to the content of the strings, improving readability and streamlining development.

### Installation

1. Open Visual Studio Code.
2. Go to the Extensions view (Ctrl+Shift+X or Cmd+Shift+X on Mac).
3. Search for **JS String Syntax**.
4. Click "Install."

### Feedback

Your feedback is invaluable! If you encounter any issues or have suggestions for improvements, please [report them](https://github.com/ericgomez/vscode-js-string-syntax/issues) here.

### License

This extension is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

Enjoy coding with **JS String Syntax**! 🚀
