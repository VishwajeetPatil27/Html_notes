
---

# What is HTML?

* **HTML** stands for **Hyper Text Markup Language**
* HTML is the standard markup language for creating Web pages
* HTML describes the structure of a Web page
* HTML consists of a series of elements
* HTML elements tell the browser how to display the content
* HTML elements label pieces of content such as:

  * "this is a heading"
  * "this is a paragraph"
  * "this is a link"

---

# A Simple HTML Document

## Example

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

## Explanation

* `<!DOCTYPE html>` → Defines this document as HTML5
* `<html>` → Root element of an HTML page
* `<head>` → Contains meta information
* `<title>` → Title shown in browser tab
* `<body>` → Contains visible page content
* `<h1>` → Large heading
* `<p>` → Paragraph

---

# HTML Attributes

* All HTML elements can have attributes
* Attributes provide additional information
* Attributes are specified in the start tag
* Usually written as: `name="value"`

---

## The `href` Attribute

The `<a>` tag defines a hyperlink.

```html
<a href="https://www.w3schools.com">Visit W3Schools</a>
```

---

## The `src` Attribute

The `<img>` tag embeds an image.

```html
<img src="img_girl.jpg">
```

### Types of URLs:

### 1️⃣ Absolute URL

```html
src="https://www.w3schools.com/images/img_girl.jpg"
```

* Links to external website image
* May have copyright issues
* Cannot control external images

### 2️⃣ Relative URL

```html
src="img_girl.jpg"
src="/images/img_girl.jpg"
```

* Links to image within same website
* Recommended approach

---

## Width and Height Attributes

```html
<img src="img_girl.jpg" width="500" height="600">
```

---

## The `alt` Attribute

* Provides alternate text if image cannot load
* Important for accessibility

```html
<img src="img_girl.jpg" alt="Girl with a jacket">
```

---

## The `style` Attribute

Used to apply CSS styles inline.

```html
<p style="color:red;">This is a red paragraph.</p>
```

---

## The `lang` Attribute

Declared inside `<html>` tag.

```html
<html lang="en">
```

With country code:

```html
<html lang="en-US">
```

---

## The `title` Attribute

Displays tooltip on hover.

```html
<p title="I'm a tooltip">This is a paragraph.</p>
```

---

# Chapter Summary (Attributes)

* All HTML elements can have attributes
* `href` → Link URL
* `src` → Image path
* `width`, `height` → Image size
* `alt` → Alternate text
* `style` → Inline CSS
* `lang` → Page language
* `title` → Extra information tooltip

---

# HTML Paragraphs

```html
<p>This is a paragraph.</p>
```

* Always starts on a new line
* Browser adds margin automatically

---

# HTML Horizontal Rule

```html
<hr>
```

* Creates thematic break
* Displays horizontal line

---

# HTML Line Break

```html
<br>
```

* Adds new line without new paragraph

---

# HTML `<pre>` Element

* Displays preformatted text
* Preserves spaces and line breaks

```html
<pre>
This is
preformatted
text.
</pre>
```

---

# HTML Style Attribute

## Syntax

```html
<tagname style="property:value;">
```

---

## Background Color

```html
<p style="background-color:yellow;">
```

---

## Text Color

```html
<p style="color:red;">
```

---

## Font Family

```html
<h1 style="font-family:verdana;">Heading</h1>
```

---

## Font Size

```html
<h1 style="font-size:300%;">Heading</h1>
```

---

## Text Alignment

```html
<h1 style="text-align:center;">Centered Heading</h1>
```

---

# Chapter Summary (Style)

* `background-color` → Background
* `color` → Text color
* `font-family` → Font type
* `font-size` → Text size
* `text-align` → Alignment

---

# HTML Formatting Elements

| Tag        | Description      |
| ---------- | ---------------- |
| `<b>`      | Bold text        |
| `<strong>` | Important text   |
| `<i>`      | Italic text      |
| `<em>`     | Emphasized text  |
| `<mark>`   | Highlighted text |
| `<small>`  | Smaller text     |
| `<del>`    | Deleted text     |
| `<ins>`    | Inserted text    |
| `<sub>`    | Subscript        |
| `<sup>`    | Superscript      |

---

## Bold and Strong

```html
<b>This text is bold</b>
<strong>This text is important!</strong>
```

---

## Italic and Emphasis

```html
<i>This text is italic</i>
<em>This text is emphasized</em>
```

---

## Small Text

```html
<small>This is smaller text.</small>
```

---

## Marked Text

```html
<p>Do not forget to buy <mark>milk</mark> today.</p>
```

---

## Deleted and Inserted

```html
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
```

---

## Subscript and Superscript

```html
<p>This is <sub>subscripted</sub> text.</p>
<p>This is <sup>superscripted</sup> text.</p>
```

---

# HTML Quotation & Citation Elements

Elements covered:

* `<blockquote>`
* `<q>`
* `<abbr>`
* `<address>`
* `<cite>`
* `<bdo>`

---

## Blockquote

```html
<blockquote cite="http://www.worldwildlife.org/who/index.html">
WWF has worked to help people and nature thrive.
</blockquote>
```

* Used for long quotations
* Usually indented

---

## Short Quote

```html
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

---

## Abbreviation

```html
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

---

## Address

```html
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
USA
</address>
```

---

## Cite

```html
<p><cite>The Scream</cite> by Edvard Munch.</p>
```

