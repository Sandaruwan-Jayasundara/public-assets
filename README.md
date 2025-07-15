# FormaText Editor
![npm](https://img.shields.io/npm/v/forma-text)
![AI Powered by Gemini](https://img.shields.io/badge/AI%20Powered%20by-Gemini-blue?logo=google)

**FormaText** is a modern, feature-rich, and highly customizable **React text editor** with **AI integration**. It provides a seamless and intuitive editing experience, offering both standard and advanced features to support a wide range of use cases—from simple text input to rich content editing.

---

## 🚀 Installation

```bash
npm install forma-text
```

<sub>**Fully compatible with React 18**</sub>

---



## 🧑‍💻 Usage

Here's a basic example of how to use the `TextEditor` component in your React application:

```jsx
import { useState } from "react";
import FormaText from "forma-text";

function App() {
  const [content, setContent] = useState("<p>Hello, world!</p>");

  return (
    <FormaText
      content={content}
      setContent={setContent}
      geminiApiKey="YOUR_GEMINI_API_KEY"
      theme="classic" // Options: "classic", "modern", "futuristic"
    />
  );
}

export default App;
```

---

## ✨ Features
![FormaText Screenshot](https://raw.githubusercontent.com/Sandaruwan-Jayasundara/public-assets/main/formatext.png)


## 🎨 Theme Variants

FormaText comes with **three beautifully designed themes**, allowing you to tailor the editor's look and feel to your application:

| Theme          | Preview                                                                                                                |
|----------------|------------------------------------------------------------------------------------------------------------------------|
| **Classic**    | ![Classic Theme](https://raw.githubusercontent.com/Sandaruwan-Jayasundara/public-assets/main/themes/classic.png)       |
| **Modern**     | ![Modern Theme](https://raw.githubusercontent.com/Sandaruwan-Jayasundara/public-assets/main/themes/modern.png)         |
| **Futuristic** | ![Futuristic Theme](https://raw.githubusercontent.com/Sandaruwan-Jayasundara/public-assets/main/themes/futuristic.png) |

> ✨ Each theme is crafted with unique UI elements, and toolbar styles for different user preferences.


---

### 🤖 AI Features
  - Refactor code blocks within the editor
  - Improve SEO automatically
  - Reorganize and optimize content using SEO best practices
  - Rewrite enhance content
-   Rich text formatting and real-time preview
-   Import Word documents 
-   Display diff tracking to compare content versions


### ✅ Standard Features

- **Basic Text Formatting**: Bold, Italic, Underline, Strikethrough, Superscript, and Subscript.
- **Headings and Paragraphs**: Switch between different heading levels and paragraph styles.
- **Font Customization**: Change font family and size.
- **Text & Highlight Colors**: Full-color palette for text and background.
- **Lists**: Ordered & unordered lists with indentation.
- **Text Alignment**: Left, center, and right alignment options.
- **Links**: Add/edit hyperlinks with a modal.
- **Block Elements**: Blockquotes, code blocks, and horizontal lines.
- **Undo/Redo**: Full undo and redo support.
- **Emoji Picker**: Rich emoji selection.
- **Clear Formatting**: Remove all styles from selected text.


### 🔒 Premium Features

- **AI-Powered Refactoring** _(with **`geminiApiKey`**)_:
  - Improve clarity, grammar, and flow using Google Gemini AI.
  - Get intelligent suggestions with a highlighted diff view.
- **Image Insertion**:
  - Upload and embed images.
  - Resize images after inserting.
  - Store image as a Base64 string.
- **Video Embedding**: Embed YouTube/Vimeo videos by URL.
- **Table Creation**: Add customizable tables.
- **Multi-Column Layouts**: Easily structure content with columns.
- **Word (.docx) Import**: Import directly from Word files.
- **Full-Screen Mode**: Distraction-free editing.
- **Source View**: View and edit raw HTML.

For production or extended access and features, contact us at: [https://exivio.net/contact](https://exivio.net/contact)

## ⚙️ Component Props

| Prop                | Type     | Default | Description                                     |
| ------------------- | -------- | ------- | ----------------------------------------------- |
| `content`           | string   | `""`    | The HTML content to be displayed and edited.    |
| `setContent`        | function | `""`    | Function called with updated content.           |
| `geminiApiKey`      | string   | `""`    | Your Google Gemini API key for AI refactoring.  |
| `parentEditorClass` | string   | `""`    | Custom CSS class for the main editor container. |
| `toolBarClass`      | string   | `""`    | Custom CSS class for the toolbar.               |
| `textContentClass`  | string   | `""`    | Custom CSS class for the content area.          |

---
## 📄 License

This project is licensed under the **MIT License**.\
See the [LICENSE](./LICENSE) file for more details.
