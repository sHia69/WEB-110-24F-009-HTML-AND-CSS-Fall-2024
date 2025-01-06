## **HTML Cheat Sheet**

### **1. Document Structure**

- **Doctype Declaration:**  
  ```html
  <!DOCTYPE html>
  ```
  - Declares the document as HTML5.

- **Basic HTML Template:**
  ```html
  <html>
    <head>
      <title>Page Title</title>
      <meta charset="UTF-8">
    </head>
    <body>
      <!-- Page content goes here -->
    </body>
  </html>
  ```
  - `<html>`: Root element of the document.
  - `<head>`: Contains metadata like title, charset, and links to stylesheets.
  - `<body>`: Contains all the visible content of the page.

### **2. Head Elements**
- **Metadata:**
  ```html
  <meta charset="UTF-8">
  ```
  - Defines the character set (UTF-8 is standard).

- **Page Title:**
  ```html
  <title>Document Title</title>
  ```
  - Sets the title displayed in the browser tab.

- **Linking Stylesheets:**
  ```html
  <link rel="stylesheet" href="styles.css">
  ```
  - Links an external CSS file.

### **3. Text-Level Elements**

#### **Basic Formatting**
- **Bold:**
  ```html
  <strong>Important text</strong>
  ```
  - Used for strong emphasis.

- **Italic:**
  ```html
  <em>Emphasized text</em>
  ```
  - Used for emphasized text.

- **Underline:**
  ```html
  <u>Underlined text</u>
  ```
  - Adds underline to the text.

- **Strike-through:**
  ```html
  <del>Deleted text</del>
  ```
  - Indicates deleted or irrelevant text.

#### **Subscript and Superscript**
- **Superscript:**
  ```html
  H<sup>2</sup>O
  ```
  - Raises text above the baseline.

- **Subscript:**
  ```html
  CO<sub>2</sub>
  ```
  - Lowers text below the baseline.

#### **Quotes and Citations**
- **Inline Quote:**
  ```html
  <q>This is a quote.</q>
  ```
  ```html
  <blockquote> content</blockquote>
  ```
  - Displays a short inline quote.

- **Citations:**
  ```html
  <cite>Cited work title</cite>
  ```
  - Cites a title of a work.

#### **Code and Preformatted Text**
- **Inline Code:**
  ```html
  <code>print('Hello, world!')</code>
  ```
  - Displays a piece of code.

- **Preformatted Text:**
  ```html
  <pre>
  Preformatted text
  is displayed exactly
  as written.
  </pre>
  ```
  - Preserves spaces and line breaks.

- **Keyboard Input:**
  ```html
  <kbd>Ctrl + C</kbd>
  ```
  - Represents keyboard input.

#### **Other Inline Elements**
- **Small Text:**
  ```html
  <small>Small print text</small>
  ```
  - Reduces the size of the text.

- **Highlight:**
  ```html
  <mark>Highlighted text</mark>
  ```
  - Highlights text.

- **Span:**
  ```html
  <span style="color:red;">Red text</span>
  ```
  - Generic container for styling.

- **Bi-Directional Override:**
  ```html
  <bdo dir="rtl">Right to left text</bdo>
  ```
  - Overrides text direction.

### **4. Block-Level Elements**

- **Paragraph:**
  ```html
  <p>This is a paragraph.</p>
  ```
  - Defines a block of text.

- **Headings:**
  ```html
  <h1>Main Heading</h1>
  <h2>Subheading</h2>
  ```
  - Use `<h1>` to `<h6>` for headings, with `<h1>` being the most important.

- **Div:**
  ```html
  <div>Content inside a div</div>
  ```
  - Generic container for block-level content.

- **Horizontal Rule:**
  ```html
  <hr>
  ```
  - Inserts a horizontal line.

### **5. Lists**
- **Ordered List:**
  ```html
  <ol>
    <li>First item</li>
    <li>Second item</li>
  </ol>
  ```
  - Creates a numbered list.

- **Unordered List:**
  ```html
  <ul>
    <li>First item</li>
    <li>Second item</li>
  </ul>
  ```
  - Creates a bulleted list.

- **Description List:**
  ```html
  <dl>
    <dt>Term</dt>
    <dd>Definition of the term.</dd>
  </dl>
  ```
  - Creates a list of terms and descriptions.

### **6. Links and Images**
- **Hyperlink:**
  ```html
  <a href="https://example.com">Link text</a>
  ```
  - Creates a hyperlink.

- **Image:**
  ```html
  <img src="image.jpg" alt="Image description">
  ```
  - Embeds an image.

### **7. Forms**
- **Form:**
  ```html
  <form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
  </form>
  ```
  - Creates a form for user input.

### **8. Comments**
- **HTML Comment:**
  ```html
  <!-- This is a comment -->
  ```
  - Adds a comment that will not be displayed in the browser.

### **9. Character Entities**

- **Non-breaking space:**  
  `&nbsp;`

- **Greater than & Less than:**  
  `&gt;` and `&lt;`

- **Ampersand:**  
  `&amp;`

- **Copyright:**  
  `&copy;`

### **10. References and Resources**

- **W3C Validator:**  
  - Validate your HTML: [validator.w3.org](https://validator.w3.org/)

- **HTML5 Specifications:**  
  - W3C: [www.w3.org/TR/html5/](https://www.w3.org/TR/html5/)

- **HTML5 Compatibility:**  
  - Check browser support: [caniuse.com](https://caniuse.com/)

- **HTML Editors:**  
  - Notepad++: [notepad-plus-plus.org](https://notepad-plus-plus.org/)

- **Web Development Tools:**
  - Visual Studio Code: [code.visualstudio.com](https://code.visualstudio.com/)
  - Sublime Text: [www.sublimetext.com](https://www.sublimetext.com/)
