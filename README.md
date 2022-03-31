# Skill Devlopment (HTML)
---
* **HTML** uses elements to describe the structure of the page.
* Tags act like containers they tell you about the information that lies between their opening and closing tags.
* **Attributes** tell us more about the element and that attributes provides additional information about the contents of an element. They appear on the opnening tag of the elments and are made up off two parts **name** and **value** separated by an '=' sign.  
* Example : `<img src="download.jpg" >`
*  The attribute name indicates what kind of extra information your supplying about element content. It should be written in lower case.
*  The value is the information or settings for the attributes. It should be placed in "double quotes ".
*  Different attributes can have different values.
*  Here an attribute called **_'src'_** is used to indicate the source used in the element. The value of this attribute on this page specifies the picture to be displayed.
* The majority of attributes can only be used on certain elements. Most attributes values are either pre-defined or follow a stipulated format.
---

## HTML tag references

* `<html>` Defines the root of the html document. 
* `<h1>` to `<h6>` defines Heading.
* `<a>` : This tag defines a hyperlink the **'href'** attribute specifies the **url** of the page the link goes to. 
  Example: `<a href="http://www.google.com">Open Google</a>`.
* Lang attribute should always include inside html tag to declare language of the html file, this is meant to assist search engines and browsers.
  Example: `<html lang="en">`.
* country codes can also be used or added to the language code such as "en-US" or "en-UK".
  Example: `<html lang="en-US">` - so the first two characters define the language of html and the last two character define the country.
* The value of the title attribute will be displayed as a tool tip when you move over the `<p title="element">element.</p>`
* Double quotes around attribute values are most common in html but single quotes can also be used in some situations where the attribute value itself contains double quotes that is necessary to use single quotes
---
## Headings
* headings vary from `<h1>` to `<h6>`, <`h1>` is most important heading where's `<h6>` defines least important heading.
* Each Html has a default size, however you can specify the size for any heading with the style attribute, using css font-size property 
---
## Paragraph
* A paragraph always starts on a new line and it is usually a block of text, where html paragraph `<p>` element defines a paragraph.
* A paragraph always starts on a new line and browser automatically adds some white spaces before and after a paragraph. Example: `<p> Hi this is a paragraph </p>`
* To separate a paragraph html horizontal rule can be applied. The `<hr>` tag defines a thermatic break in a html page and most of it display as a horizontal rule.
* It is also used to seprate 
---

## HTML Style
* Html Style is used to add styles to an element such as color, font size, font and many more... Example: `<h1 style="font-size:60px;">`.
* The css background color property, the background color of an html element. Example: `<p style="background-color: black;">`
* **Fonts**: The css font family property defines, the font to be used for an html element.
* You can increase the size of text or a paragraph of an html element
* Html comments are not displayed  on the browser but they can help document your html source code. Example: `<!-- this is a comment -->`
---

## CSS
* Css saves a lot of work. It can control the layout of multiple webpages all at once.
* Definition: it is used to format the layout of the webpage. with css u can control the color, font, the size of the text, the spacing between the elements, how elements are positioned and layed out, what background images are background colors are to be used,  different displays for different devices and screen size and more.
---

# DAY 2 
## --- Exercise 1 ---
1. `<p title="About HTML"> HTML is Hypertext mark up language.</p>`

2. set the size of the img 250px wide and 400px tall
    `<img src="downloads.jpg" width="250px" height="400px">`
3. make the elements below into a link that goes to www.google.com
    `<a href="https://www.google.com">This is a link</a>`
4. Specify an alternate text for the image to show alternate text is usefull when the image can't be displayed like when the page is read by a screen reader.
    `<img src="MS Office.png"  alt="Microsoft Office Logo">`
5. Use the correct HTML tag to add a heading with a text "London".

    ```html 
    <h1>London</h1>
    <p>London is the capital city of England. It is the most Populus city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
    ```
    
6. Add six headings to the document with the text "Hello".
   Start with the most important heading (the largest) and end with the least important heading (the smallest).
   
   ```html
   <html>
        <body>
            <h1>Hello</h1>
            <h2>Hello</h2>
            <h3>Hello</h3>
            <h4>Hello</h4>
            <h5>Hello</h5>
            <h6>Hello</h6>
        </body>
    </html>
    ```
    
    <html>
        <body>
            <h1>Hello</h1>
            <h2>Hello</h2>
            <h3>Hello</h3>
            <h4>Hello</h4>
            <h5>Hello</h5>
            <h6>Hello</h6>
        </body>
    </html>
7. Mark up the text with appropriate tags.
    * "Universal Studios Presents" is the most important heading.
    * "Jurassic Park" is the next most important heading.
    * "About" is the third most important heading.
    * The last sentence is jusa a paragraph.
    * Start with the most important heading (the largest) and end with the least important heading (the smallest).
    
    ```html
    <h1>Universal Studio Presents</h1>
    <h2>Jurassic Park</h2>
    <h3>About</h3>  
    <p>On the Island of Isla Nublar, a new park had been built: Jurassic Park is  a theme park of cloned dinosaurs!!</p>
    ```
    
    <h1>Universal Studio Presents</h1>
    <h2>Jurassic Park</h2>
    <h3>About</h3>  
    <p>On the Island of Isla Nublar, a new park had been built: Jurassic Park is  a theme park of cloned dinosaurs!!</p>
8. Use the correct HTML tag to add a paragraph with the text "Hello World!".

    ```html
    <html>
        <body>
            <p>Hello World!</p>
        </body>
    </html>
    ```
    
    <p>Hello World!</p>
9. Clean up this document with proper end tags

    ```html
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
    ```
    
10. Add a horizontal rule between the heading and the paragraph.

    ```html
    <h1>London</h1>
    <hr>
    <p>London is the capital city of England. It is the most populus city in the United Kingdom, with a metropolitan area of over 13 million inhabitanta.</p>
    ```
    
    <h1>London</h1>
    <hr>
    <p>London is the capital city of England. It is the most populus city in the United Kingdom, with a metropolitan area of over 13 million inhabitanta.</p>
11. Add a line break in the middle of the paragraph.
    
    `<p>My Bonnie lies <br> over the ocean.</p>`
    
    <p>My Bonnie lies <br> over the ocean.</p>
12. Wrap this poem around HTML tags that will preserve all spaces and linebreaks when the element is displayed.

    ```html
    <pre>
        My Bonnie lies over the ocean.
        My Bonnie lies over the sea.
        My Bonnie lies over the table.
    </pre>
    ```
    
    <pre>
        My Bonnie lies over the ocean.
        My Bonnie lies over the sea.
        My Bonnie lies over the table.
    </pre>
13. Use the correct HTML attribute, and CSS, to set the color of the paragraph to "blue".
    `<p style="color: bule;">This is a paragraph.</p>`
    [This is a paragraph.]()
14. Use CSS to set the font of the paragraph to "courier".
    `<p style="font-family: courier;">This is a paragraph.</p>`
    <p style="font-family: courier;">This is a paragraph.</p>
15. Use CSS to center align the paragraph.
    `<p style="text-align: center;">This is paragraph.</p>`
    <p align=center>This is paragraph.</p>
16. Use CSS to set the text size to 50 pixels.
    `<p style="font-size: 50px;">This is a paragraph.</p>`
    <p style="font-size: 50px;">This is a paragraph.</p>
17. Use CSS to set the background color of the document to yellow.

    ```
    <html>
        <body style="background-color: yellow;">
            <h1>This is a heading</h1>
            <p>This is a paragraph.</p>
        </body>
    </html>
    ```
    
> <html>
> <body >
>            <h1>This is a heading</h1>
>            <p>This is a paragraph.</p>
>       </body>
>    </html>
18. Use CSS to center align the document.

    ```
    <html>
        <body style="text-align: center;">
            <h1>This is a heading </h1>
            <p>This is a paragraph.</p>
        </body>
    </html>
    ```
    
    <html>
        <body >
            <h1 align=center>This is a heading </h1>
            <p align=center>This is a paragraph.</p>
        </body>
    </html>
19. Add extra importance to the word "degradation" in the paragraph below.
    
    `<p> WWF's mission is to stop the <strong> degradation </strong> of our planet's natural environment.</p>`
    WWF's mission is to stop the **degradation** of our planet's natural environment.
20. Emphasize the word "metropolitan" in the text below.

    ```html
    <h1>Tokyo</h1>
    <p>Tokyo is the capital of Japan, the most populous <emp>metropolitan</emp> area in the world.</p>
    ```
    
# Tokyo
  Tokyo is the capital of Japan, the most populous _metropolitan_ area in the world.

21. Highlight the word "FUN" in the text below.
    `<p>HTML is <mark>FUN</mark> to learn!</p>`
22. Apply subscript formatting to the number "2" in the text below.
    `<p>H<sub>2</sub>0 is the scientific term for water</p>`
    <p>H<sub>2</sub>0 is the scientific term for water</p>
23. Add a line through  (strikeout) the letters "blue" in the text below.
    `<p>My favorite color is <del>blue</del> red.</p>`
    <p>My favorite color is <del>blue</del> red.</p>
24. Use the HTML comment tag to make a comment out of the "This is comment" text.

    ```html
    <h1>This is a heading</h1>
    <!--This is a comment-->
    <p>This is a paragraph.</p>
    ```
    
25. Add comment tags around the paragraph:
    `<!--<p>This is a paragraph.</p>-->`
---

## 1. Write a program to create a html page as shown 

```html
  <html>
        <head>
            <title>Maths</title>
        </head>
        <body>
            <h1>Squares of Numbers</h1>
            <p>1<sup>2</sup> = 1 </p>
            <p>2<sup>2</sup> = 4 </p>
            <p>3<sup>2</sup> = 9 </p>
            <p>4<sup>2</sup> = 16 </p>
            <p>10<sup>2</sup> = 100 </p>
        </body>
  </html>
```

<h1>Squares of Numbers</h1>
<p>1<sup>2</sup> = 1 </p>
<p>2<sup>2</sup> = 4 </p>
<p>3<sup>2</sup> = 9 </p>
<p>4<sup>2</sup> = 16 </p>
<p>10<sup>2</sup> = 100 </p>

---

## HTML Tables 
* A table represents information in a grid format.
* example of tables include financial reports, TV schedule and sports result.
* Grids allow us to understand complex data by referencing information on two axis
* Each block in the grid is refered to as a table cell. In html a table is written out by rows.  
   `<table>`
* the table tag element is used to create a table. The contents of the table are written out by row.
    `<tr>`
* You indicate the start of each row using the opening tag tr(table row).
* it is followed by one or more td (one for each cell in that row).
* At the end of the row you use `</tr>` tag for closing.
    `<td>`
* Each cell of a table is represented using a td(table date) tag element.
* At the end of each cell you should use `</td>` for closing 
    `<th>`
* The th(table head) tag element is used just like td tag element but it's purpose is to represent the heading for either a column or a row.
* Even if a cell has no content you should still use td or th element's to represent the presence of an empty cells otherwise it'll not render correctly 
* Using th element for heading helps people who use screen readers, improves the abitlity of search engines to index your pages, and also enables you to control the appearence of the table. you can use the scope attribute on the th element to indicate wheather it is a heading for a column or a row. It can take values row to indicate heading for a row, col to indicate a heading for a column.

#### Example

```html 
<table>
      <tr>
        <td>15</td>
        <td>15</td>
        <td>30</td>
      </tr>
      <tr>
        <td>45</td>
        <td>60</td>
        <td>45</td>
      </tr>
      <tr>
        <td>60</td>
        <td>90</td>
        <td>90</td>
     </tr>
</table>
```

<table>
    <tr>
        <td>15</td>
        <td>15</td>
        <td>30</td>
    </tr>
    <tr>
        <td>45</td>
        <td>60</td>
        <td>45</td>
    </tr>
    <tr>
        <td>60</td>
        <td>90</td>
        <td>90</td>
    </tr>
</table>

|no| tag             |            Description
|-|------------------|----
|1| `<table>`    | Defines a table                                                   
|2| `<th>`    | Defines a header cell in a table      
|3| `<tr>`       | Defines a row in a table                                  
|4| `<td>`       | Defines a cell in a table
|5| `<caption>`  | Defines a table caption                                           
|6| `<colgroup>` | Specifies a group of one or more columns in a table for formatting
|7| `<thead>`    | Groups a header content in a table
|8|`<col>`   | It is used with ```<colgroup>``` element to specify column properties for each column.
|9|`<tbody>` | It is used to group the body content in a table.
|10| `<tfooter>` |   It is used to group the footer content in a table.


```
 <table>
    <tr>
        <th></th>
        <th scope="col">Saturday</th>
        <th scope="col">Sunday</th>
    </tr>
    <tr>
        <th scope="row">Tickets sold:</th>
        <td>120</td>
        <td>135</td>
    </tr>
    <tr>
        <th scope="row">Total sales:</th>
        <td>$600</td>
        <td>$675</td>
    </tr>
</table>
```

<table>
    <tr>
        <th></th>
        <th scope="col">Saturday</th>
        <th scope="col">Sunday</th>
    </tr>
    <tr>
        <th scope="row">Tickets sold:</th>
        <td>120</td>
        <td>135</td>
    </tr>
    <tr>
        <th scope="row">Total sales:</th>
        <td>$600</td>
        <td>$675</td>
    </tr>
</table>

<table border="2px">
        <tr>
            <th colspan="7" style="color: red">TIME TABLE FOR MCA C SEC</th>
        </tr>
        <tr>
            <th style="color: blue">DAYS</th>
            <td>1st</td>
            <td>2nd</td>
            <td rowspan="6" style="transform: rotate(45deg);">Short Break</td>
            <td>3rd</td>
            <td>4th</td>
            <td>5th</td>
            <td>6th</td>
        </tr>
            <tr>
            <td>MONDAY</td>
            <td>RDBMS</td>
            <td>P AND S</td>
            <td>OS</td>
            <td>DS</td>
            <td>SE</td>
            <td>WEB LAB</td>
        </tr>
        </tr>
            <tr>
            <td>TUESDAY</td>
            <td>RDBMS</td>
            <td>OS</td>
            <td>DS</td>
            <td>LIBRARY</td>
            <td>WEB</td>
            <td>P AND S</td>
        </tr>
        </tr>
            <tr>
            <td>WEDNESDAY</td>
            <td>RDBMS</td>
            <td>WEB TECH</td>
            <td>SE</td>
            <td>P AND S</td>
            <td>OS LAB</td>
            <td>DS</td>
        </tr>
        <tr>
            <td>THURSDAY</td>
            <td>RDBMS LAB</td>
            <td>DS</td>
            <td>SE</td>
            <td>WEB TECH</td>
            <td>OS</td>
            <td></td>
        </tr>
            <tr>
            <td>FRIDAY</td>
            <td>DS LAB</td>
            <td>RDBMS</td>
            <td>WEB TECH</td>
            <td>P AND S</td>
            <td>SE</td>
            <td></td>
        </tr>
    </table>
                                
* Long tables there are three elements that help distinguish between the main content of the table and the first and the last rows which can contain diffrent content 
* Example: 
* These elements help people who use screen readers and also allow you to style these sections

---

## background-color of table and border
* The border attribute is used on both table and td elements to indicate the width of the border in pixels

```
<table border="2" bgcolor="#a3e4f9">
    <tr>
        <th width="150"></th>
        <th>Withdrawn</th>
        <th>Credit</th>
        <th width="150" bgcolor="#cccccc">Balance</th>
    </tr>
    <tr>
        <td>January</td>
        <td>250.00</td>
        <td>660.50</td>
        <td bgcolor="#bbc6c8">410.50</td>
    </tr>
    <tr>
        <td>February</td>
        <td>135.55</td>
        <td>895.20</td>
        <td bgcolor="#cccccc">1170.15</td>
    </tr>
</table>
```

<table border="2" bgcolor="#a3e4f9">
    <tr>
        <th width="150"></th>
        <th>Withdrawn</th>
        <th>Credit</th>
        <th width="150" bgcolor="#cccccc">Balance</th>
    </tr>
    <tr>
        <td>January</td>
        <td>250.00</td>
        <td>660.50</td>
        <td bgcolor="#bbc6c8">410.50</td>
    </tr>
    <tr>
        <td>February</td>
        <td>135.55</td>
        <td>895.20</td>
        <td bgcolor="#cccccc">1170.15</td>
    </tr>
</table>

* The background color attribute is used to indicate background color of entire table or individual cells in a table. 
* The width attribute was used in the opening of a table tag to indicate the width of each row.

---

## Using CSS 
* Css can be added to html in 3 different ways 
    1. Inline - by using style attribute inside Html element.
    2. Internal - by using style element.
    3. External - by using link element to link external css file.
### Inline Css 
* An inline css is used to apply a unique style to a single html element
* An inline css used the style attribute of an Html element 
* Example : 

``` 
<h1 style="color: blue;">A Blue heading</h1>
            <p style="color: red;">This is a Paragraph</p>
```

### Internal Css
* Internal Cssis used to design or style a single html pages
* an Internal Css file is descibed in head part of the html within style element
* Example : 

```
<html>
    <head>
        <style> 
            body {
                background-color: powderblue;
                }
            h1 {
                color: blue;
                }
            p {
                color: red;
                }
        </style>
    </head>
    <body>
        <h1>This is heading tag</h1>
        <p>This is a paragraph</p>
        </body>
</html>
```
<html>
    <head>
        <style> 
            body {
                background-color: powderblue;
                }
            h1 {
                color: blue;
                }
            p {
                color: brown;
                }
        </style>
    </head>
    <body>
        <h1>This is heading tag</h1>
        <p>This is a paragraph</p>
        </body>
</html>

### External Style Sheet
* An external style sheet is used to style for many html pages.
* The external style sheet can be written in any text edittor the file must not contain any html codes and must be saved with .css extension
* Example : 
```
<html>
    <head>
        <link rel="stylesheet" type="text/css" href="style.css">
        </head>>
    <body>
        <h1>This is heading tag</h1>
        <p>This is a paragraph</p>
    </body>
</html>
**Style.css**
h1 {
    background-color: blue;
    }
```

### Css Border
* The css border property defines a border around an html element.
* You can define a border for nearly all html elements
* Example : p {  border: 2px solid powderblue;}
### Css Padding
* The css padding property defines a padding between the text and the border.
* Example : p { padding: 10px;}
### Css Margin
* The css margin property defines margin outside the border 
* Example : p { margin: 30px;}
### Link to External Css
* External style sheet can be referenced with a full url or with a path relative to the current webpage.
* Example : ```<link rel="stylesheet" type="text/css" href="http://www.facebook.com">```
### Links
* Links are found in nearly all the webpages, Links allows users to click thier way from page to page
* Hyperlinks - html links are hyperlinks, You can click on a link and jump to another document when you move the mouse over a link the mouse arrow will turn into a little hand.
    + A link doesn't have to be a text, A link can be an image or any other html elements.  
* Html links - the target attribute
* By default the link page will be displayed in the current browser window, to change this you must specify another target for the link.
* the target attribute can have one of the following values 
    1. **_self** - by default opens a document in the same tab or window as it was clicked.
    2. **_blank** - opens a document in new window or tab.
    3. **_parent** - opens a document in the parent frame.
    4. **_top** - opens a document in the full body of the window.

# DAY 3
---

### Relative URL and Absolute URL.
* A link to a page within the same website is specified with relative URL (without the "http://www.").
* Absoulute URL uses full web adress in the **href** attribute.
* Example: 

```html
<a href="image1.jpg"> <!--Relative URL-->
<a href="http://www.google.com"> <!--Absolute URL-->
```

### Use image as a link.
* To use image as a link just add imag tag inside the a tag.
* Example:

```
<a href="default.asp"><img src="image.jpg" alt="Html tutorial" style="width:42px; height: 42px;"></a>
<a href="http://www.google.com">
```

### Button as a link.
* To use html button as a link you need to add some javascript code.
* Javascript allows you to specify what happens at cetain events such as click of a button.
* Example : `<button onclick="document.location='default.asp'"></button>`


## Css selector.
* There are many diffrent types of css selector that allows you to target rules to specific element in an html page or document.
* Css selector are case sensitive so they must match elements names and attribute values exactly.

### Universal Selector
* Applies to all the elements in the document.
* Example : `*{}`

### Type Selector.
* h1 selector mathces element name' 
* Example : `h1{},h2{}`

### Class Selector.
* Matches an element whose class attribute has a value that matches the one specified after a period (.) symbol.
* Example : `.note{} , p.note{} `

### Id Selector.
* Matches an element who id attribute has a value that matches the one specified after a hash or pound (#) symbol.
* Example : `#introduction{}`

### Child Selector.
* Matches an element that is direct child of another.
* Example : `li> a{}`
* Targets any a tag element that are children of a li tag element (but not other a tag element in a page).

### Descendent Selector.
* Matches an element that is a descendent of another specified element (not just a direct child of that element).
* Example : `p a {}`

### General Sibling.
* Matches an element that is a sibling of another, although it doesn't have to be direct preceeding element.
* Example : `h1-p {}`

### Adjacent Sibling.
* Matches an element that is a next sibling of another.
* Example : `h1+p {}`

### Html class attribute 
* It is used to specify class for an html element. Multiple Html elements can share the same class. The class attribute is often used to point to a class name in a stylesheet. It can also be used by a javascript to access and manipulate elements with a specific class name
* Example :
```
<!DOCTYPE html>
<html>
<head>
<style>
    .city {
        background-color: tomato;
        color: white;
    }
</style>
</head>
<body>
    <div class="city">
        <h2>London</h2>
        <p>London is the capital of England.</p>
    </div>
    <div class="city">
        <h2>Paris</h2>
        <p>Paris is the capital of France.</p>
    </div>
</body>
</html>
```
* In the above example we have 2 div tag elements with a class attribute with a value of city all two div elements will be styled equally according to the .city style definition in the head section.

```
<<!DOCTYPE html>
<html>
<head>
    <style>
        .note {
            font-size: 120%;
            color: red;
        }
    </style>
    <title></title>
</head>
<body>
    <h1>My <span class="note">Important</span> Heading</h1>
    <p>This is some <span class="note">important</span> text.</p>
</body>
</html>
```

### The Syntax for Class.
* To create a class write a period (.) symbol, followed by a class name. Then define the css properties within curly braces.

### Multiple classes 
* Html element can belong more than one classes. To define Multiple classes separate the classes name with a spaces the element will be styled according to all the clasess specified. 
* Example : 
```html 
<div class="city name">
    <h1 class="city main">London</h1>
    <h2 class="city">Paris</h2>
```
* The above example the h1 element belong to both the city class and also the main class and will get css style from both of the classes.

### Diffrent elements can share same class.
* Example : 
```html
<div class="city main">
    <h1 class="city main">London</h1>
    <p>London is the capital of England.</p>
    <h2>Paris</h2>
    <p>Paris is the capital of France.</p>
</div>
```
* In the above example both h2 and p points to the city class and will share same style.