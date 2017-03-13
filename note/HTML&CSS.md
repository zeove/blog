---
layout: note
---


1、The `<!DOCTYPE html>` declaration should always be the first line of code in your HTML files.

2、The `<html>` element will contain all of your HTML code.

3、Information about the web page, like the title, belongs within the `<head>` of the page.

4、You can add a title to your web page by using the `<title>` element, inside of the head.

5、Code for visible HTML content will be placed inside of the `<body>` element.

---

1、You can add headings of different sizes using the different headings elements: `<h1>` through `<h6>`.

2、Paragraphs are added with the `<p>` element.

3、Unordered lists are created with the `<ul>` element and list items are added using the `<li>` element.

4、Ordered lists are created with the `<ol>` element and list items are added using the `<li>` element.

5、You can add links to your web page using the `<a>` element - don't forget the href attribute!

6、Images can be added with the `<img>` element - don't forget the src attribute!

7、Images help support visually impaired users when `<img>` elements include the alt attribute.

8、You can turn anything into a link by wrapping it with an `<a>` element.

9、White space in the HTML file does not affect the positioning of elements in the browser.

10、The W3C recommends 2 spaces of indentation for nested HTML elements.

11、Comments are used to take notes inside of an HTML file. You can add a comment with `<!-- This is a comment -->`.

---

1、HTML and CSS are kept in separate files in order to keep code maintainable and readable, as well as keep structure separate from styling.

2、The `<style>` element allows you to write CSS code within an HTML file.

3、A CSS stylesheet can be linked to an HTML file using the `<link>` element, which requires three attributes:

> `href` - set equal to the path of the CSS file.

> `type` - set equal to text/css.

> `rel` - set equal to stylesheet.

---

1、A CSS selector targets an HTML element.

2、CSS declarations style HTML elements. Declarations must contain the following two things:

> `property` - the property you want to style.

> `value` - the value for the property you are styling.

3、CSS declarations must end in a semicolon `(;)`

4、A CSS rule consists of a CSS selector and the declarations inside of the selector.

5、Multiple element selectors can be used to style multiple elements at once.

6、Comments keep code easy to read and allow you to experiment with new code without having to remove old code.

7、CSS follows certain best practices for spacing and indentation:

> One line of spacing between a selector and the opening curly brace.

> No spacing between CSS declarations and the opening and closing curly braces of the CSS rule.

> Two spaces of indentation for CSS declarations.

> One line of spacing between CSS rules.

---

1、Foreground color refers to the actual color of an element, styled with the `color` property.

2、Background color refers to the color behind an element, styled with the `background-color` property.

3、There are 147 named colors available.

4、RGB and hexadecimal colors offer over 16 million color possibilities.

5、HSL is a new way of defining colors in CSS3.

6、You can modify the opacity of a color with `RGBa` or `HSLa` colors.

7、Not all browsers support newer CSS features, like opacity or HSL, so additional declarations should be made to support a wide audience of users.

8、There are many color picker resources available on the Internet to help you select specific colors, as well as provide colors in different formats.

---

1、The `font-family` property changes the typeface of text.

2、`Serif` fonts have extra details on the ends of each letter. `Sans-Serif` fonts do not.

3、Fallback fonts are used when a certain font is not installed on a user's computer.

4、Google Fonts provides free fonts that can be used in an HTML file with the `<link>` element.

5、Font size can be specified using pixels, ems, or percentages.

6、The vertical spacing between lines of text can be modified with the `line-spacing` property.

7、The horizontal spacing between words can be modified with the `word-spacing` property.

8、The spacing between letters, the kernel, can be modified with the `letter-spacing` property.

9、Text can appear bold with the `font-weight` property.

10、Text can appear in italics with the `font-style` property.

11、Text can appear in all uppercase or all lowercase with the `text-transform` property.

12、Text can be aligned with the `text-align` property.

---

1、Code is a lot more readable when it is organized using IDs, classes, and divs.

2、IDs label HTML elements that are unique to the web page (an element that appears only once).

3、Classes label elements that will share the same styling. They make styling more efficient.

4、The `<div>` groups elements together. It makes the HTML file easier to read by organizing the web page into logical sections.

5、HTML elements can be labeled with multiple classes.

6、Divs are one of the most commonly used HTML elements. Understanding how they are used is a critical skill for web developers.

---

1、All HTML elements are contained within a box.

2、Boxes have two dimensions: a width and a height. These dimensions can be modified with the `width` and `height` properties.

3、Width and height dimensions can be set using one of three units of measurement: pixels, ems, or percentages.

4、A minimum and maximum width or height can be set for a box. This helps ensure that content remains legible when a user shrinks or expands their browser window.

5、If an element's box becomes too small, the content may overflow. The overflowed content can be controlled with the `overflow` property.

---

1、You can style the borders of an element's box.

2、The `border-width` property allows you to set the thickness, or width, of a border.

3、The `border-style` property allows you to change the style of border used.

4、The `border-color` property allows you to change the color of a border.

5、Individually setting the style, thickness, and color of a border can bloat code. It's more efficient to use the shorthand border property and specify all three properties at once, in that order.

6、Box borders don't have to be square. Their corners can be rounded with the `border-radius` property.

---

1、`Padding` is the spacing between a box's content and the borders of the box.

2、`Padding` can be set equally on all sides of the content, or can be set specifically for certain sides of the content only.

3、`Margin` is the spacing directly outside of a box's borders.

4、`Margins` can be set equally on all sides of a box, or can be set specifically for certain sides of the box only.

5、The `display` changes the default behavior of HTML elements.

6、The `visibility` property hides an element, but does not remove the amount of space the element takes up on the page. If you want to hide that element and remove the empty space, use the `display` property instead.

---

1、In the default box model, box dimensions are affected by border thickness and padding.

2、The `box-sizing` property controls the box model used by the browser.

3、The default value of the `box-sizing` property is `content-box`.

4、The value for the new box model is `border-box`.

5、The `border-box` model is not affected by border thickness or padding.

---

1、The `position` property allows you to specify the position of an element in three different ways.

2、When set to `relative`, an element's position is relative to its default position on the page.

3、When set to `absolute`, an element's position can be pinned to any part of the web page, but the element will still move out of view the page is scrolled.

4、When set to `fixed`, an element's position can be pinned to any part of the web page. The element will remain in view no matter what.

5、The `z-index` of an element specifies how far back or how far forward an element appears should appear on the page.

6、The `float` property can move elements as far left or as far right as possible on a web page.

7、You can clear an element's left or right side (or both) using the `clear` property.