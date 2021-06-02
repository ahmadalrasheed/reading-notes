# what is CSS?
CSS (Cascading Style Sheets) allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.
![CSS](https://www.freetutorialsplus.com/css-tutorial/images/css-illustration.png)
***Prerequisites: Basic computer literacy, basic software installed, basic knowledge of working with files, and HTML basics (study Introduction to HTML.)***

## What is CSS for?
this cascading style sheet language is used for styling our our website , HTML cant be used for styling but CSS is using for styling and coloring our website,in addition, it can be used for effects such like animation.
## CSS syntax
if I want the main heading on my page to be shown as large red text , The following code shows a very simple CSS rule that would achieve the styling described above:

`h1 {
    color: red;
    font-size: 5em;
}`

h1 here is the header in the HTML code , and here we modified it to be in `RED` and large `font`

and this is another example to convert paragraph color into black color

`p {
    color: black;
}
`
## How To Add CSS

### Three Ways to Insert CSS

There are three ways of inserting a style sheet:

* External CSS
* Internal CSS
* Inline CSS

## External CSS
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

## Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the <style> element, inside the head section.

## Inline CSS

this type of CSS is used in HTML code `inline of HTML CODE`

## CSS color Property
Example

Set the text-color for different elements:

`body {
  color: red;
}`

`h1 {
  color: #00ff00;
}`

`p.ex {
  color: rgb(0,0,255);
}
`
## Definition and Usage

The `color` property specifies the color of text.

and here is an example to convert the color of all of the paragraphs in body into light blue color.

`body {color: #92a8d1;}`


