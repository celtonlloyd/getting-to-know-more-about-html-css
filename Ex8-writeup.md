# Getting to know more about HTML and CSS
## Semantic Code
Sematic code helps the machine, screen readers and search engine optimizers to understand the meaning of the code  
Elements like `<div>`and `<span>` are non semantic tags and are used for styling purposes while `<section>, <header>, <nav>, <footer>, <article>` etc are the sematic tags and are used to give a semantic meaning and provides structure to the content.

## Elements
There are different kinds of elements. `<div>` and `<span>` are used for styling purposes.  
Headings `<h1>` and paragraphs `<p>` are text based elements  
Inline elements like `<em> and <b>`are used to style within the text based elements

Hyperlinks are used to open up other pages or links. There are 2 kinds,  
 Relative path : Used to open an internal page within the current document  .
  Absolute path : Used to open an external document.

The `<img>` element is used to attach images to the document

## CSS resets
Css resets are used to remove all the pre-defined styles from the elements since differnt browsers display them differently. Here is how Eric Meyer's reset looks like
```
 /* http://meyerweb.com/eric/tools/css/reset/
   v2.0 | 20110126
   License: none (public domain)
  */

  html, body, div, span, applet, object, iframe,
  h1, h2, h3, h4, h5, h6, p, blockquote, pre,
  a, abbr, acronym, address, big, cite, code,
  del, dfn, em, img, ins, kbd, q, s, samp,
  small, strike, strong, sub, sup, tt, var,
  b, u, i, center,
  dl, dt, dd, ol, ul, li,
  fieldset, form, label, legend,
  table, caption, tbody, tfoot, thead, tr, th, td,
  article, aside, canvas, details, embed,
  figure, figcaption, footer, header, hgroup,
  menu, nav, output, ruby, section, summary,
  time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
  }
  /* HTML5 display-role reset for older browsers */
  article, aside, details, figcaption, figure,
  footer, header, hgroup, menu, nav, section {
    display: block;
  }
  body {
    line-height: 1;
  }
  ol, ul {
    list-style: none;
  }
  blockquote, q {
    quotes: none;
  }
  blockquote:before, blockquote:after,
  q:before, q:after {
    content: '';
    content: none;
  }
  table {
    border-collapse: collapse;
    border-spacing: 0;
  }
  ```
  From here on we can add indivisual styles to our content and will be able to re-write the reset due to the Cascading rule. In cascading whatever styles come at the bottom will have more precedence than the earlier one.

  Selectors hold different specificity weight based on it 
  `Type: 0-0-1
  Class: 0-1-0
  ID: 1-0-0`  

  Selectors can also be combined and differnt properties and values like color and font size can be added to it.

