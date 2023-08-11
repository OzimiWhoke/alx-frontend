# CSS

CSS (Cascading Style Sheets) are used to style HTML.

CSS works by:

- selecting an HTML element
- choosing a property to alter
- applying a certain value

Applying CSS can be done by using:

- External stylesheet:
An external stylesheet contains CSS in a separate file with a .css extension. This is the most commonly used method of adding CSS to a document. You can also link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet.
this style uses the link; <link rel="stylesheet" href="styles.css"> to linked to the HTML codes.
The external file will look like this;
h1 {
  color: deepskyblue;
  text-align: center;
}

- Internal stylesheet:
An internal stylesheet resides within an HTML document. To create an internal stylesheet, just place CSS code inside a <style> element contained inside <head> element of the HTML.
It looks like this in an HTMl document;
<head>
  <meta charset="utf-8">
  <title>Adding Styles</title>
  <style>
    h1 {
      color: deepskyblue;
      text-align: center;
    }
  </style>
</head>

- Inline style:
Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute.

Example of an inline style in an HTML document:

<h1 style="color: deepskyblue; text-align: center;">Hello CSS!</h1>

