# Section 1.1
### 1. What is a markup language?
A **markup language** is a way of writing documents that include instructions on how the text should look or be structured. It's used to create web pages. Examples are HTML, which makes web pages, and XML, which organizes data.

### 2. What is XHTML? How does XHTML differ from HTML?
**XHTML** is a version of HTML that is stricter and follows more precise rules, similar to XML. 

**Differences between XHTML and HTML:**
- **Rules:** XHTML has stricter rules. For example, every tag must be closed, and tags should be written in lowercase.
- **Structure:** XHTML requires that all tags be properly nested (you can't close a tag before closing the tags inside it).
- **Empty Tags:** Tags like `<br>` must be written as `<br />` in XHTML.

### 3. What is the W3C? What is the WHATWG?
- **W3C (World Wide Web Consortium):** The W3C is a group that creates standards for the web to make sure it works well for everyone.
- **WHATWG (Web Hypertext Application Technology Working Group):** The WHATWG is another group that works on developing web standards, especially focused on practical use and improvements for web developers.

### 4. What is a doctype? What is the doctype for an HTML5 document?
A **doctype** is a declaration at the top of an HTML document that tells the browser which version of HTML is being used, so it can display the page correctly.

The **doctype** for an HTML5 document is:
```html
<!DOCTYPE html>
```

### 5. What is incorrect about the following code? Suggest a possible revision of the code to correct the error.
**Incorrect code:**
```html
<p><strong>Curbside Thai now delivers!</p></strong>
```
**Problem:** The `<strong>` tag isn’t properly closed before the closing `</p>` tag, which is incorrect.

**Corrected code:**
```html
<p><strong>Curbside Thai now delivers!</strong></p>
```
This version closes the `<strong>` tag correctly before the paragraph ends.

### 6. Provide code to mark "Curbside Thai Employment Opportunities" as the document title.
```html
<title>Curbside Thai Employment Opportunities</title>
```

### 7. Provide code to create metadata adding the keywords "food truck, North Carolina, and dining" to the document.
```html
<meta name="keywords" content="food truck, North Carolina, dining">
```

### 8. Provide code to tell the browser that the character encoding UTF-16 is used in the document.
```html
<meta charset="UTF-16">
```

### 9. Provide code to add the comment "Created by Sajja Adulet" to the document.
```html
<!-- Created by Sajja Adulet -->
```
# Section 1.2
### 1. Provide code to mark the text "Gourmet Thai Cooking" as a heading with the second level of importance.
```html
<h2>Gourmet Thai Cooking</h2>
```
This code uses the `<h2>` element, which represents a heading with the second level of importance.

### 2. What element should you use to mark page content as a sidebar?
The `<aside>` element is used to mark content as a sidebar. The `<aside>` element typically contains content that is related to the main content but is not part of it, such as sidebars, pull quotes, or advertisements.

### 3. What is the `div` element, and why will you often encounter it in pre-HTML5 code?
The `<div>` element is a block-level container used to group content together for styling or layout purposes. 

**Why it's common in pre-HTML5 code:**
- Before HTML5 introduced semantic elements like `<header>`, `<footer>`, `<article>`, and `<section>`, developers often used `<div>` to structure web pages. It was the most common way to organize and apply CSS styles to different parts of a page.
  
### 4. What element would you use to indicate a change of topic within a section?
The `<section>` or `<hr>` element could be used to indicate a change of topic within a section.

- **`<section>`:** This is more appropriate when the content needs to be grouped semantically within a section.
- **`<hr>`:** This element represents a thematic break and can be used to visually separate different topics.

### 5. Provide the code to mark the text "Daily Special" as emphasized text.
```html
<em>Daily Special</em>
```
The `<em>` element is used to emphasize text, which is often rendered in italics by default.

### 6. Provide the code to mark the text "H₂SO₄" with subscripts.
```html
H<sub>2</sub>SO<sub>4</sub>
```
This code uses the `<sub>` element to create subscripts for the chemical formula.

### 7. Provide the code to link the web page to the CSS file "mystyles.css."
```html
<link rel="stylesheet" href="mystyles.css">
```
This code links the HTML document to an external CSS file named "mystyles.css."

### 8. Provide the expression to insert an em dash into a web page using the character code 8212.
```html
&mdash;
```
This code inserts an em dash (—) using the HTML entity for the character code 8212.

### 9. Provide the code to insert an inline image using the source file "awlogo.png" and the alternate text "Art World."
```html
<img src="awlogo.png" alt="Art World">
```
This code inserts an inline image with the source file "awlogo.png" and provides alternate text "Art World" for accessibility and in case the image fails to load.
# Section 1.3
### 1. Provide the code to mark the unordered list containing the items: Packers, Vikings, Bears, Lions.
```html
<ul>
  <li>Packers</li>
  <li>Vikings</li>
  <li>Bears</li>
  <li>Lions</li>
</ul>
```

### 2. Provide the code to mark the following list of the top-five most popular movies ranked in descending order according to IMDB:
   5. Pulp Fiction
   4. The Dark Knight
   3. The Godfather: Part II
   2. The Godfather
   1. The Shawshank Redemption
```html
<ol>
  <li>The Shawshank Redemption</li>
  <li>The Godfather</li>
  <li>The Godfather: Part II</li>
  <li>The Dark Knight</li>
  <li>Pulp Fiction</li>
</ol>
```

### 3. Describe the three HTML elements used in a description list.
- `<dl>`: Defines the description list.
- `<dt>`: Defines a term (name) in the list.
- `<dd>`: Defines the description for the term.

### 4. Provide the code to create a navigation list for the following list items: Home, FAQ, Contact Us and pointing to the index.html, faq.html, and contacts.html files respectively.

```html
<ul>
  <li><a href="index.html">Home</a></li>
  <li><a href="faq.html">FAQ</a></li>
  <li><a href="contacts.html">Contact Us</a></li>
</ul>
```

### 5. Using the folder structure shown in Figure 1-40, provide the relative path going from the `ct_about.html` file to the `ct_catering.html` file.

Assuming the folder structure shown in Figure 1-40 is typical, the relative path would be:
```
../ct_catering.html
```

### 6. Provide the URL pointing to the element in the `glossary.html` file with the ID `c_terms`. Assume that the glossary.html file is in the same folder as the current page.

```
glossary.html#c_terms
```

### 7. Provide the URL to access the website at the address www.example.com/curbside over a secure connection.

```
https://www.example.com/curbside
```

### 8. Provide the URL for an e-mail link to the address sajja@curbside.com with the subject line FYI.

```
mailto:sajja@curbside.com?subject=FYI
```

### 9. Provide the URL for a telephone link to the U.S. phone number 970-555-0002.

```
tel:+19705550002
```
