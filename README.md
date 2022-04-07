# Skill Devlopment (HTML)
---

### Brief History of HTML
* Once upon a time when there aren't any footprints on a moon some FARSIGHTED folks decided or major computers network together Until 1990 accessing information through the internet was a rather technical affect. It was so hard in fact even the Phd holder were often frustrated when trying to swap data. One such scientist Sir. Tim Burners Knee work on cross-reference of text on the Internet throught hypertext links. By 1993 only hundred computers thorughout the world were equipped with to server these internet pages and several web browser programs had been written to allow people to give webpages.
* From that point onwards the continued development of web browser and standardisation of the html and xhtml languages has lead us to the world we live in today. One in which more than 120 Million web servers answer request for more than 25 Billion text and Multimedia files.
* Example

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Page Title</title>
</head>
<body>
    <h1>First Heading</h1>
    <p>First Paragraph</p>
</body>
</html>
```

#### What is Html?
* Html stands for Hyper Text Markup Language where hyper text is nothing but a link created between web pages. markup language is the text between tags which defines structure. Html is language to create web pages. Html defines how the web page looks and how to display content with help of elements. It forms or defines the structure of the web pages all the files created has to be saved with .html extension.
* It is easy to learn and create effective presentation.
* It also allows the user to add links where we can add references.
* We can also display documents on platforms like mac, windows, linux etc.
* Adding vido's, graphics and audio's does not attract the viewers 
* Html is case insensitive language.
* `<!DOCTYPE html>` Instruction to the browser about the html version(html5).
* `<html>` Root element which act as a container to hold all the code, browser should know that this is a html document. Committed content one `<head>` tags followed by one `<body>` tag.
* `<head>` Everything written here will never be displayed in the browser. It contains general info about the document i.e, `<title>` definition of file, Css stylesheet, `<meta>` Information about the document.
* `<body>` everthing written here will be displayed which contans `<image>`, `<text>`, `<link>` which can achived thorugh tags.
    * Example : `<p>Hello Everyone</p>`
                `<img src="download.jpg">`
* **HTML** uses elements to describe the structure of the page.
* Tags act like containers they tell you about the information that lies between their opening and closing tags.
* **Attributes** tell us more about the element and that attributes provides additional information about the contents of an element. They appear on the opnening tag of the elments and are made up off two parts **name** and **value** separated by an '=' sign.  
* Example : ```<img src="download.jpg" >```
*  The attribute name indicates what kind of extra information your supplying about element content. It should be written in lower case.
*  The value is the information or settings for the attributes. It should be placed in "double quotes ".
*  Different attributes can have different values.
*  Here an attribute called **_'src'_** is used to indicate the source used in the element. The value of this attribute on this page specifies the picture to be displayed.
* The majority of attributes can only be used on certain elements. Most attributes values are either pre-defined or follow a stipulated format.
---

## HTML tag references

* ```<html>``` Defines the root of the html document. 
* ```<h1>``` to ```<h6>``` defines Heading.
* ```<a>``` : This tag defines a hyperlink the **'href'** attribute specifies the **url** of the page the link goes to. 
  Example: ```<a href="http://www.google.com">Open Google</a>```.
* Lang attribute should always include inside html tag to declare language of the html file, this is meant to assist search engines and browsers.
  Example: ```<html lang="en">```.
* country codes can also be used or added to the language code such as "en-US" or "en-UK".
  Example: ```<html lang="en-US">``` - so the first two characters define the language of html and the last two character define the country.
* The value of the title attribute will be displayed as a tool tip when you move over the ```<p title="element">element.</p>```
* Double quotes around attribute values are most common in html but single quotes can also be used in some situations where the attribute value itself contains double quotes that is necessary to use single quotes
---
## Headings
* headings vary from ```<h1>``` to ```<h6>```, <```h1>``` is most important heading where's ```<h6>``` defines least important heading.
* Each Html has a default size, however you can specify the size for any heading with the style attribute, using css font-size property 
---
## Paragraph
* A paragraph always starts on a new line and it is usually a block of text, where html paragraph ```<p>``` element defines a paragraph.
* A paragraph always starts on a new line and browser automatically adds some white spaces before and after a paragraph. Example: ```<p> Hi this is a paragraph </p>```
* To separate a paragraph html horizontal rule can be applied. The ```<hr>``` tag defines a thermatic break in a html page and most of it display as a horizontal rule.
* It is also used to seprate 
---

## HTML Style
* Html Style is used to add styles to an element such as color, font size, font and many more... Example: ```<h1 style="font-size:60px;">```.
* The css background color property, the background color of an html element. Example: ```<p style="background-color: black;">```
* **Fonts**: The css font family property defines, the font to be used for an html element.
* You can increase the size of text or a paragraph of an html element
* Html comments are not displayed  on the browser but they can help document your html source code. Example: ```<!-- this is a comment -->```
---

## CSS
* Css saves a lot of work. It can control the layout of multiple webpages all at once.
* Definition: it is used to format the layout of the webpage. with css u can control the color, font, the size of the text, the spacing between the elements, how elements are positioned and layed out, what background images are background colors are to be used,  different displays for different devices and screen size and more.
---

# DAY 2 
## --- Exercise 1 ---
1. ```<p title="About HTML"> HTML is Hypertext mark up language.</p>```

2. set the size of the img 250px wide and 400px tall
    ```<img src="downloads.jpg" width="250px" height="400px">```
3. make the elements below into a link that goes to www.google.com
    ```<a href="https://www.google.com">This is a link</a>```
4. Specify an alternate text for the image to show alternate text is usefull when the image can't be displayed like when the page is read by a screen reader.
    ```<img src="MS Office.png"  alt="Microsoft Office Logo">```
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
    
    ```<p>My Bonnie lies <br> over the ocean.</p>```
    
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
    ```<p style="color: bule;">This is a paragraph.</p>```
    [This is a paragraph.]()
14. Use CSS to set the font of the paragraph to "courier".
    ```<p style="font-family: courier;">This is a paragraph.</p>```
    <p style="font-family: courier;">This is a paragraph.</p>
15. Use CSS to center align the paragraph.
    ```<p style="text-align: center;">This is paragraph.</p>```
    <p align=center>This is paragraph.</p>
16. Use CSS to set the text size to 50 pixels.
    ```<p style="font-size: 50px;">This is a paragraph.</p>```
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
    
    ```<p> WWF's mission is to stop the <strong> degradation </strong> of our planet's natural environment.</p>```
    WWF's mission is to stop the **degradation** of our planet's natural environment.
20. Emphasize the word "metropolitan" in the text below.

    ```html
    <h1>Tokyo</h1>
    <p>Tokyo is the capital of Japan, the most populous <emp>metropolitan</emp> area in the world.</p>
    ```
    
# Tokyo
  Tokyo is the capital of Japan, the most populous _metropolitan_ area in the world.

21. Highlight the word "FUN" in the text below.
    ```<p>HTML is <mark>FUN</mark> to learn!</p>```
22. Apply subscript formatting to the number "2" in the text below.
    ```<p>H<sub>2</sub>0 is the scientific term for water</p>```
    <p>H<sub>2</sub>0 is the scientific term for water</p>
23. Add a line through  (strikeout) the letters "blue" in the text below.
    ```<p>My favorite color is <del>blue</del> red.</p>```
    <p>My favorite color is <del>blue</del> red.</p>
24. Use the HTML comment tag to make a comment out of the "This is comment" text.

    ```html
    <h1>This is a heading</h1>
    <!--This is a comment-->
    <p>This is a paragraph.</p>
    ```
    
25. Add comment tags around the paragraph:
    ```<!--<p>This is a paragraph.</p>-->```
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
   ```<table>```
* the table tag element is used to create a table. The contents of the table are written out by row.
    ```<tr>```
* You indicate the start of each row using the opening tag tr(table row).
* it is followed by one or more td (one for each cell in that row).
* At the end of the row you use ```</tr>``` tag for closing.
    ```<td>```
* Each cell of a table is represented using a td(table date) tag element.
* At the end of each cell you should use ```</td>``` for closing 
    ```<th>```
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
|1| ```<table>```    | Defines a table                                                   
|2| ```<th>```    | Defines a header cell in a table      
|3| ```<tr>```       | Defines a row in a table                                  
|4| ```<td>```       | Defines a cell in a table
|5| ```<caption>```  | Defines a table caption                                           
|6| ```<colgroup>``` | Specifies a group of one or more columns in a table for formatting
|7| ```<thead>```    | Groups a header content in a table
|8|```<col>```   | It is used with ```<colgroup>``` element to specify column properties for each column.
|9|```<tbody>``` | It is used to group the body content in a table.
|10| ```<tfooter>``` |   It is used to group the footer content in a table.


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
* Example : ```<button onclick="document.location='default.asp'"></button>```


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

# Exercise 2
1. Use css to set the background color of the document to yellow and also include the heading as 'my homepage'.
    ```
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            body {
                background-color: yellow;
            }
        </style>
    </head>
    <body>
        <h1>My Homepage</h1>
    </body>
    </html>
    ```
2. Use css to set the font of the document to courier.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            body {
                font-family: courier;
            }
        </style>
    </head>
    <body>
        <h1>My Homepage</h1>
    </body>
    </html>
    ```
3. Use css to make a yellow, 1px thick border around all paragraph. and include atleast 3 diffrent paragraph.
    ```html
    <<!DOCTYPE html>
    <html>
    <head>
        <style>
            p{ border: 1px solid yellow; }
        </style>
    </head>
    <body>
        <p>This is paragraph 1</p>
        <p>This is paragraph 1</p>
        <p>This is paragraph 1</p>
    </body>
    </html> 
    ```
4. Use the correct HTML to make the text below into a link to "default.html".
    *   ```<a href="default.html">Visit our HTML tutorial</a>```
5. Use css to remove the underline from the link.
    *   ```<a href="html_images.asp" style="text-decoration:none;">HTML Images</a>```
6. Use the correct HTML attribute to make the link open in a new window.
    *   ```<a href="html_images.asp" target="_blank">HTML Images</a>```
7. Use the correct HTML to make the image become a link to "default.html".
    *   ```<a href="default.html"> 
            <img src="smiley.gif">
        </a>```
8. Add a tooltip to the link and the tooltip should say "Home".
    *   ```<a href="default.html" title="home">Back to Home</a>```
9. In the style section create a class selector named special and add a color property with the value blue inside the special class. Apply this style to a paragraph.
    *   
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            .special {
                color: blue;
            }
        </style>
    </head>
    <body>
        <p class="special">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
        tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
        quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
        consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
        cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
        proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    </body>
    </html>
    ```
10. Create a class mystyle with the character properties as color red and add this class to the heading my home.
    *   
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            .myStyle {
                color: red;
            }
        </style>
    </head>
    <body>
        <h1 class="myStyle">My Home.</h1>
    </body>
    </html>
    ```
11. Add two classes to the heading element to make the background color pink and the text color as red.
    *
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            .class1 {
                background-color: pink;
            }
            .class2 {
                color: red;
            }
        </style>
    </head>
    <body>
        <h1 class="class1 class2">This is Heading.</h1>
    </body>
    </html>
    ```

### Html Lists.
* Html list allows web developpers to group a set of relative items in list. There are two types **Unordered** and **ordered**. 
    - Undordered
        + Apple
        + Ball
        + Cat
        + Dog
        + Elephant
    - Ordered
        1. Apple
        2. Ball
        3. Cat
        4. Dog
        5. Elephant

* Unordered list starts with ul tag element. Each list item starts with li tag.
* An ordered list starts with ol tag. Each list item starts with li tag.

12. Add list items with the text Apple, Ball, Cat, Dog, Elephant as unordered list.
    ```html
    <!DOCTYPE html>
    <html>
    <body>
        <ul>
            <li>Apple</li>
            <li>Ball</li>
            <li>Cat</li>
            <li>Dog</li>
            <li>Elephant</li>
        </ul>
        <ol>
            <li>Apple</li>
            <li>Ball</li>
            <li>Cat</li>
            <li>Dog</li>
            <li>Elephant</li>
        </ol>
    </body>
    </html>
    ```
### Description List
* Description list is list of terms with the description of each term. The dl tag defines the description list, the dt tag defines the term(name) and the dd tag describes each term.
* Example : 
    ```html
    <!DOCTYPE html>
    <html>
    <body>
        <dl>
            <dt>Coffee</dt>
            <dd>Coffee is brown in color</dd>
            <dt>Milk</dt>
            <dd>Milk is white in color</dd>
        </dl>
    </body>
    </html>
    ```
13. Use Css to display squares instead of bullets.
    ```html
    <ul style="list-style-type: square;">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
    </ul>
    ```
14. Use the correct HTML attribute to display letters (uppercase ABC) instead of numbers.
    ```html
    <ol type="A">
        <li>Coffee</li>
        <li>Tea</li>
        <li>Milk</li>
    </ol>
    ```
15. Use the correct HTML elements to make a description of each term in the description list.
    ```html
    <dl>
        <dt>Coffee</dt>
        <dd>- black hot drink</dd>
        <dt>Milk</dt>
        <dd>- white cold drink</dd>
    </dl>
    ```
### id Attribute
* specifies a unique id for an html element, the value of the id attribute must be unique within the html document. The id attribute is used to point a specific style declaration in a stylesheet, the syntax for id is hash(#) charcter followed by an id name. Then define the css properties within the curly braces.
* Example : 
    ```html
    <!DOCTYPE html>
    <html>
    <head>
        <style>
            #myheader{
                background-color: lightblue;
                color: black;
            }
        </style>
    </head>
    <body>
        <h1 id="myheader">My Header</h1>
    </body>
    </html>
    ```
### Iframe
* An html iframe is used to display a webpage within a webpage.
#### Syntax
* In html iframe tag specifies an inline frame is used embed another document within the current html document.
* `<iframe src="url" title="description"></iframe>`
* You can set height and width of the frame by specifying the height and width.
* `<iframe src="url" height="200" width="400" title="description"></iframe>`
* You can add diffrent style by using style attribute.
* `<iframe src="url" style="height:200px;width:400;" title="description"></iframe>`
#### iframe removing the border.
* You can add or remove the border by adding the style attribute and use the css border property.
* `<iframe src="url" style="border:none;" title="description"></iframe>`
#### target for a link.
* An iframe can be used as a traget for a link. The target attribute of the link referes to name attribute of the frame.
* Example : 
```
<iframe src="demo_iframe.html" name="iframe_a" title="iframe example"></iframe>
<p><a href="http://www.google.com" target="iframe_a">Google</a></p>
```

#### Html Javascript
* The javascript makes the html pages more dynamic and interactive. The html script tag is used to define a client side script(javascript). The script element either contains script statement or a point to an external source through the src attribute.
#### The head element 
* The html head element is a container for following elements.
    ```+ <title>
    + <style>
    + <link>
    + <script>
    + <meta> and <base>
    ```
* meta tag defines  about an html element, meata tags always go inside the head element 
__
* meta data will not be displayed on the page. meta date is used by the browser(how to display content or reload page), search engines and other web services.
* For search engines.
    `<meta name="keywords" content="HTML, CSS, JavaScript">`
* Define a description of your web page.
    `<meta name="description" content="Free Web tutorials  for HTML and CSS">`
* Refresh document every 30 seconds:
    `<meta http-equiv="refresh" content="30">`
#### div tag
* div tag defines a division or a section in a html document and it is used as a container for html elements, which is then styled with CSS or JavaScript. The div tag is easily styled by using class or id attributes.

#### Span Tag
* span tag is an inline container used to markup a part of text or a part of document.
* Example : 
    ```<p>My mother has <span style="color:blue;">blue</span> eyes.</p>```

#### Css Comments
* Css comments are used to explain the code, and help when you edit the source code.
* Example 1: 
    ```/* This is a single-line comment */```
* Example 2: 
    ``p {
        color: red;     /* set text color to red */
    }``
#### Background Colors in Css
* background color in css is same as that of html but it is initialized in a separate way.
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        p{
            background-color: red;
        }
    </style>
</head>
<body>
    <h2>My Heading</h2>
</body>
</html>
```
#### Opacity or Transparency
* Opacity property specifies the Opacity or Transparency of an element. 
* It can take value from 0.0 to 1.0 lower the value the more transparent. 
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        p{
            background-color: red;
        }
    </style>
</head>
<body>
    <h2>My Heading</h2>
</body>
</html>
```

#### Background Image 
* It specifies an image to use background of an element, by default the image is repeated so it covers the entire element.
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body{
            background-image: url("Image1.jpg");
        }
    </style>
</head>
<body>
    <h2>My Heading</h2>
</body>
</html>
```
#### Background Attachment
* It specifies wheather the background image should scroll or be fixed.
* Background repeat by default the property repeats an image both horizontally and vertically, but some images should be reapeated only horizontally or vertically else they'll look strange.
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <style>
        body{
            background-image: url("Image1.jpg");
            background-repeat: repeat;
            background-repeat: repeat-x;
            background-repeat: repeat-y;
            background-repeat: no-repeat;
            background-position: center;
            background-position: left;
            background-position: right;
            background-position: right top;
            background-position: top;
            background-position: bottom;
            background-attachment: fixed;
        }
    </style>
</head>
<body>
    <h2>My Heading</h2>
</body>
</html>
```
#### CSS Background Shorthand
* To shorten the code it is also possible to specify all the background properties in one single property.
* Example :
```body {
    background-color: red;
    background-image: url("image1.png");
    background-repeat: no-repeat;
    background-position: right top;
}
```
# DAY 3
---

### CSS Font
* Css font and thier properties can be defined .
1. Font-family is used to change the face of a font.
    + Example : 
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="font-family:georgia,garamond,serif;">
            This text is rendered in either georgia, garamond, or the default serif font depending on which font you have at your system.
        </p>        
    </body>
    </html>
    ```

2. Font-style is used to make a font itallic or oblique.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="font-style: italic;">
            This text is rendered in either georgia, garamond, or the default serif font depending on which font you have at your system.
        </p>        
    </body>
    </html>
    ```  
3. Font-varient is used to create small capital effect.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="font-variant: small-caps;">
            This text is rendered in either georgia, garamond, or the default serif font depending on which font you have at your system.
        </p>
    </body>
    </html>
    ```  
4. Font-weight is used to increase or decrease how bold or light a font appears.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="font-weight: bold;">
            This font is bold.
        </p>   
        <p style="font-weight: bolder;">
            This font is bolder.
        </p>        
        <p style="font-weight: 500;">
            This font is bold.
        </p>     
    </body>
    </html>
    ```  
5. Font-size is used to increase or decrease the size of the font.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
            <p style="font-size: 20px;">
                This font size is 20 pixels.
            </p>
            <p style="font-size: small;">
                This font size is small.
            </p>        
            <p style="font-size: large;">
                This font size is large.
            </p>        
            <p style="font-size-adjust: 0.61;">
                This text is using a font-size-adjust value.
            </p>    
            <p style="font-stretch: ultra-expanded;">
                This text is using a font-size-adjust value.
            </p>     
        </body>
        </html>
        ```  
    6. Font is used as short hand to specify a number of other font properties.
        + Example :
        ```html
        <!DOCTYPE html>
        <html>
        <head>
        </head>
        <body>
            <p style="font: italic small-caps 15px gerogia;">
                This text is rendered in either georgia, garamond, or the default serif font depending on which font you have at your system.
            </p>        
        </body>
        </html>
        ```  
### CSS Text
* Text and their properties 
1. Color is used set the color of the text.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="color: red;">
            This text color will be red.
        </p>        
    </body>
    </html>
    ```
2. Direction is used to set the text direction.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="direction: ltr;">
            This text will be rendered left to right.
        </p>        
    </body>
    </html>
    ```
3. Letter spacing is used to add or subtract spaces between the letters that make up a word.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="letter-spacing: 5px;">
            This text is having space between letters.
        </p>        
    </body>
    </html>
    ```
4. Word spacing is used to add add or subtract spaces between the words of sentence.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="word-spacing: 5px;">
            This text is having space between words.
        </p>        
    </body>
    </html>
    ```
5. Text indent is used to indent the text of a paragraph.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="text-indent: 1cm;">
            This text will have first line indented by 1 cm and this line will remain at its actual position this is done by CSS text-indent property.
        </p>        
    </body>
    </html>
    ```
6. Text align is used align text of document.
    + Example :
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="text-align: right;">
            This text will be right.
        </p>
        <p style="text-align: center;">
            This text will be center.
        </p>        
        <p style="text-align: left;">
            This text will be left.
        </p>                
    </body>
    </html>
        ```
7. Text decoration is used to underline, overline, and strikethrough text.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="text-decoration: underline;">
            This text will be underlined.
        </p>
        <p style="text-decoration: line-through;">
            This text will be striked through.
        </p>        
        <p style="text-decoration: overline;">
            This text will have a over line.
        </p>
        <p style="text-decoration: blink;">
                This text will have blinking effect.
        </p>                
    </body>
    </html>
    ```
8. Text transform is used to capitalize text or convert text to uppercase or lower case.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="text-transform: capitalize;">
            This text will be capitalized.
        </p>
        <p style="text-transform: uppercase;">
            This text will be uppercase.
        </p>        
        <p style="text-transform: lowercase;">
            This text will be lowercase.
        </p>                
    </body>
    </html>
    ```
9. Whitespace is used to control the flow and formatting of text.
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="white-space: pre;">
            This text has a line break and the white-space pre setting 
            tells the browser to honor it just like the HTML pre tag.
        </p>
    </body>
    </html>
    ```
10. Text shadow is used to set text shadow around a text. 
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    </head>
    <body>
        <p style="text-shadow: 4px 4px 8px blue;">
            If your browser supports the CSS text-shadow property, this text will have a blue shadow.
        </p>
    </body>
    </html>
    ```

### CSS Links
1. The **:link** signifies unvisited hyperlinks.
2. The **:visited** signifies visited hyperlinks.
3. The **:hover** signifies an element that currently has the user mouse pointer hovering over it.
4. The **:active** signifies an elment on which the user is currently clicking.
Example : 
    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <style type="text/css">
        a:link {color:#000000};
        a:visited{color:#006600};
        a:hover{color:#efcc00};
        a:active{color:#cdfhcc};
    </style>
    </head>
    <body>
        <a href="http://www.google.com">Link</a>
        <a href="http://www.facebook.com">Link</a>
        <a href="http://www.instagram.com">Link</a>
        <a href="http://www.yahoo.com">Link</a>
    </body>
    </html>
    ```

### CSS Tables
* The **border-collapse** specifies whether the browser should control the appearance of the adjacent borsers that touch each other or whether each cell should maintain its style.
* The **border-spacing** specifies the width that should appear between table cells.
* The **caption-side** captions are presented in the `<caption>` element. By default, these are rendred above the table in the doucment. You use the caption-side property to control the placement of the table caption.
* The **empty-cells** specifies whether the border should be shown if a cell is empty.
* The **table-layout** allows the browser to speed up layout of the table by using the first width properties it comes across for the rest of a column rather than having to load the whole table before rendering it.
* border-collapse Example :
```html
<!DOCTYPE html>
<html>
<head>
    <style type="text/css">
        table.one {border-collapse: collapse;}
        table.two {border-collapse: separate;}

        td.a {
            border-style: dotted;
            border-width: 3px;
            border-color: #000000;
            padding: 10px;
        }
        td.b {
            border-style: solid;
            border-width: 3px;
            border-color: #333;
            padding: 10px;
        }
    </style>
</head>
<body>
    <table class="one">
        <caption>Collapse Border Example</caption>
        <tr>
            <td class="a">Cell A Collapse Example</td>
        </tr>
        <tr>
            <td class="b">Cell B Collapse Example</td>
        </tr>
    </table>
    <br/>
    <table class="two">
        <caption>Separate Border Example</caption>
        <tr>
            <td class="a">Cell A Separate Example</td>
        </tr>
        <tr>
            <td class="b">Cell B Separate Example</td>
        </tr>
    </table>
</body>
</html>
```
* border-spacing Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <style type="text/css">
        table.one {
            border-collapse: separate;
            width: 400px;
            border-spacing: 10px;
        }
        table.two {
            border-collapse: separate;
            width: 400px;
            border-spacing: 10px;
        }
    </style>
</head>
<body>
    <table class="one" border="1">
        <caption>Collapse Border Example border-spacing</caption>
        <tr>
            <td>Cell A Collapse Example</td>
        </tr>
        <tr>
            <td>Cell B Collapse Example</td>
        </tr>
    </table>
    <br/>
    <table class="two" border="1">
        <caption>Separate Border Example border-spacing</caption>
        <tr>
            <td>Cell A Separate Example</td>
        </tr>
        <tr>
            <td>Cell B Separate Example</td>
        </tr>
    </table>
</body>
</html>
```

* caption-side Example :
```html
<!DOCTYPE html>
<html>
<head>
    <style type="text/css">
        table.empty {
            border-collapse: separate;
            width: 400px;
            border-spacing: 10px;
        }
        table.two {
            border-collapse: separate;
            width: 400px;
            border-spacing: 10px;
        }
    </style>
</head>
<body>
    <table class="one" border="1">
        <caption>Collapse Border Example border-spacing</caption>
        <tr>
            <td>Cell A Collapse Example</td>
        </tr>
        <tr>
            <td>Cell B Collapse Example</td>
        </tr>
    </table>
    <br/>
    <table class="two" border="1">
        <caption>Separate Border Example border-spacing</caption>
        <tr>
            <td>Cell A Separate Example</td>
        </tr>
        <tr>
            <td>Cell B Separate Example</td>
        </tr>
    </table>
</body>
</html>
```

### CSS Border
* The border properties allow you to specify how the border of the box representing an element should look.
* There are three properties of a border you can change -
    + The **border-color** specifies the color of a border.
    + The **border-style** specifies wether a border should be solid, dashed line, double line, or one of the other possible values.
    + The **border-width** specifies the width of the border.
* **Value**   - Description Demo
* **none**    - Default value. Specifies no border  
* **hidden**  - The same as "none", except in border conflict resolution for table elements 
* **dotted**  - Specifies a dotted border   
* **dashed**  - Specifies a dashed border   
* **solid**   - Specifies a solid border    
* **double**  - Specifies a double border   
* **groove**  - Specifies a 3D grooved border. The effect depends on the border-color value 
* **ridge**   - Specifies a 3D ridged border. The effect depends on the border-color value  
* **inset**   - Specifies a 3D inset border. The effect depends on the border-color value   
* **outset**  - Specifies a 3D outset border. The effect depends on the border-color value  
* **initial** - Sets this property to its default value. 
* **inherit** - Inherits this property from its parent element. 
* **border-bootom-style** changes the style of bottom border.
* **border-top-style** changes the style of top border.
* **border-left-style** changes the style of left border.
* **border-right-style** changes the style of right border.


### CSS Lists
* They are very helpfull in conveying a set of either a number or bullet points.
1. **List-style-type** which allows you to control the shape or appearance of the marker.
2. The **List-style-position** specifies whether a long point that wraps to a second line should align with the first line or start underneath the start of the marker.
3. **List-style-image** specifies an image for the marker rather than a bullet point or a number.
4. **List-style** serves as shorthand for the preceding properties.
5. **Marker-offset** specifies the distance between marker and the text in the list.

|Sr.No | Value & Description |  |
|-------| ------------------------| -----------------|
|1 |none| |
| |NA| |
|2|disc(default)| |
| |A filled-in circle | |
|3|circle | |
| |(an empty circle)| |
|4|square | |
| |(a filled in square)| |

| Value | Description | Example |
|-------|-------------|---------|
| decimal | Number | 1,2,3,4,5|
| decimal-leading-zero | 0 before the number | 01,02,03,04,05 |
| lower-alpha | Lowecase alphanumeric characters | a,b,c,d,e |
| upper-alpha | Uppercase alphanumeric characters | A,B,C,D,E |
| lower-roman | Lowercase Roman numerals | I, II, III, IV, V |
| upper-roman | Uppercase roman numerals | i, ii, iii, iv , v |
| lower-greek | The marker is lower greek | alpha, beta, gamma |
| lower-latin | The marker is lower latin | a,b,c,d,e....|
| upper-latin | The marker is upper-latin | A,B,C,D,E...|
| hebrew | The marker is traditional American numbering | | 
| armenian | The marker is traditional Armainian | |
| geogian | The marker is traditional Gerogian | |
| cjk-idographic | The marker is plain ideographic number | |
| hiragana | The marker is hiragana | a,i,u,e,o,ka,ki |
| katakana | The marker is katakana | A,I,U,E,O,KA,KI |
| hiragana-iroha | The marker is hiragana iroha | i,ro,ha,ni,ho,he,to|
| katakana-iroha | The marker is katakona iroha | I,RO,HA,NI,HO,HE,TO |

---
### write a program displaying list of items html, css, javascript in circle and square (unordered) decimal, lower alpha and lower roman(ordered).
```html
<!DOCTYPE html>
<html>
<head>
    <title>LIST</title>
</head>
<body>
    <ul style="list-style: circle;">
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ul>
    <ul style="list-style: square;">
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ul>
    <ol style="list-style: decimal;">    
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ol>
    <ol style="list-style: lower-alpha;">    
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ol>
    <ol style="list-style: lower-roman;">    
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ol>
    <ul style="list-style-image: url('https://picsum.photos/id/237/100/50');">    
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ul>

</body>
</html>
```

### Marker-offset
* **marker-offset** allows you to specify the distance between the marker and text relating to that marker.
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <title>LIST</title>
</head>
<body>
    <ul style="list-style: circle; marker-offset: 4em">
        <li>HTML</li>
        <li>CSS</li>
        <li>JAVASCRIPT</li>
    </ul>
</body>
</html>
```

### CSS Padding
* The padding property allows you to specify how much space should appear between the content of an element and it's borders.
* The value of this attribute should be either a length a percentage or the word inherit.
* Some of the properties of padding are 
1. padding-bottom specifies the bottom padding of an element.
2. padding-top specifies the top padding of an element.
3. padding-left specifies the left padding of an element.
4. padding-right specifies the right padding of an element.

* Example :
```html
<!DOCTYPE html>
<html>
<head>
    <title>Padding</title>
</head>
<body>
    <p style="padding-bottom: 20px; border: 1px solid black;">
        This is a paragraph and padding is specified for bottom.
    </p>
    <p style="padding-top: 20px; border: 1px solid black;">
        This is a paragraph and padding is specified for bottom.
    </p>
    <p style="padding-left: 20px; border: 1px solid black;">
        This is a paragraph and padding is specified for bottom.
    </p>
    <p style="padding-right: 20px; border: 1px solid black;">
        This is a paragraph and padding is specified for bottom.
    </p>
</body>
</html>
```

### CSS Panel
* The panel class adds 16 pixels top and bottom margin and 16 pixels left and right padding to any html element.
* Example : 
```html
<!DOCTYPE html>
<html>
<body>
    <div class="w3-panel w3-red">
        <p>I am Panel</p>
    </div>
</body>
</html>
```
---
# DAY 3


### CSS Box Model
* The css box model is essentially a box that wraps around every html element. It consists of margins, borders, padding and actuall content the image below illustrates the box model.
* **Content** The content of the box where the images and text appear.
* **Padding** Clears an area around the content, the padding is transparent.
* **Border** that goes around the padding and content.
* **Margin** clears an area outside the border.

```html
<!DOCTYPE html>
<html>
<head>
    <style>
        div {
        background-color: lightgrey;
        width: 300px;
        border: 15px solid green;
        padding: 50px;
        margin: 20px;
    } 
    </style>
</head>
<body>
    <h2>Demonstrating the Box Model</h2>
    <p>The CSS boc model is essentially a box that wraps around every HTML element. It consists of: borders, padding, margins, and the actual content</p>
    <div>This text is the content of the box. We have added a 50px padding, 20px margin and a 15px green border.</div>
</body>
</html>
```

### CSS Outline
* An outline is a line that is drawn around element outside the border to make the elements standou.
* Outline styles 
    + dotted - defines a dotted outline.
    + dash - defines a dash outline.
    + solid - defines a solid outline.
    + double - defines a double outline.
    + groove, ridge, inset, outset - defines 3d outline.
    + none - defines no outline.
    + hidden - a hidden outline.
* Outline width - This property specifies the width of the outline and can have one of the following values 
    Thin(1px), medium(3px), Thick(5px) and so on..., a specific size in px, pt, cm, etc...
* Outline offset - This property adds spaces between outline and the edge of an element

* CSS Text - pre-defined background color and text color of the content 

```html
<!DOCTYPE html>
<html>
<head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300&family=Roboto:wght@100;400&display=swap" rel="stylesheet">    <style>
    body{
        background-color: #cc99dd;
        color: white;
        font-weight: bolder;
        text-shadow: 2px 2px 5px black;
        font-size: 30px;
    }
    div{
        outline-color: #ccddcc;
        outline-width: 10px;
        margin: 5% 3%;
    }

    div.dotted{
        outline-style: dotted;
        letter-spacing: 5px;
    } 
    div.dashed{
        outline-style: dashed;
    }
    div.solid{
        outline-style: solid;
    } 
    div.double{
        outline-style: double;
        text-align: center;
    } 
    div.groove{
        outline-style: groove;
        text-decoration:  underline;
        font-family: 'Open Sans', sans-serif;
        font-family: 'Roboto', sans-serif;
}
    div.ridge{
        outline-style: ridge;
    } 
    div.inset{
        outline-style: inset;
        text-transform: uppercase;
    }  
    div.outset{
        outline-style: outset;
        text-indent: 50px;
    } 

    </style>
</head>
<body>
    <div class="dotted">A dotted outline</div>
    <div class="dashed">A dashed outline</div>
    <div class="solid">A solid outline</div>
    <div class="double">A double outline</div>
    <div class="groove">A groove outline</div>
    <div class="ridge">A ridge outline</div>
    <div class="inset">A inset outline</div>
    <div class="outset">A outset outline</div>

</body>
</html>
```
### [Google Fonts](https://fonts.google.com/)
* If you do not want to use any of the standard fonts in html you can use google fonts.
* Google fonts are free to use and have more than thousand fonts to choose from.

### CSS Icon
* An icon can be easily to your html page by using an icon library.
* To add icons - The simplest way to add icons to your html page with icon library.
* To add icons to hmtl add the name of the specific icon class to any inline html element all the icons in the icon library which are scalable, vectored that can customized with css
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="http://kit.fontawsome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <i class="fas fa-cloud"></i>
</body>
</html>

```
* write a program to add a link google.com, facebook.com, gmail.com, instagram.com

```html
<!DOCTYPE html>
<html>
<head>
    <style type="text/css">
        a:link {
            color: powderblue;
        }
        a:active {
            color: red;
        }
        a:hover {
            color: yellow;
        }
        a:visited {
            color: green;
        }
    </style>
</head>
<body>
    <a href="https://www.google.com">Google</a>
    <hr>
    <a href="https://www.facebook.com">Facebook</a>
    <hr>
    <a href="https://www.gmail.com">Gmail</a>
    <hr>
    <a href="https://www.instagram.com">Instagram</a>
</body>
</html>
```

* Figure Tag : figure tag element, to markup a photo in a doc
* figure caption :-element define caption for the photo
* An html uses html form is used to collect user input. The user input is most often sent to a server for processing.
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
    <title>Forms</title>
</head>
<body>
    <h1>HTML Forms</h1>
    <br>
    <form action="action_page.php">
        <label for="fname">First Name</label><br>
        <input type="text" name="fname" id="fname" value="Johny">
        <label for="lname">Last Name</label><br>
        <input type="text" name="lname" id="lname" value="sins">

    </form>
</body>
</html>
```

* Action tag : The action attribute specifies where to send the form when a form is submitted.
* Accept Charset : specifies the character encoding that are to be used for the form submission.
* Auto complete : specifies wether a form should have autocomplete on or off.
* Method : specifies the http method to use, when sending form data.
* Name : specifies the name of the form.
* Rel : specifies the relationship between the link resource and current document.
* Target : spcifies where to display the response that is received after submitting the form.
* Fieldset : It used to group related element in a form, it draws a box around the related element.


```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>Forms</title>
    <style type="text/css">
        filedset{
            background-color: red;
        }
        legend{
            background-color: grey;
            color: white;
            padding: 5px 10px;
        }
        input{
            margin: 5px;
        }
    </style>
</head>
<body>
    <h1>The fieldset element</h1>

    <form action="/action_page.php">
        <fieldset>
            <legend>Personalia:</legend>
            <label for="fname">First name:</label>
            <input type="text" id="fname" name="fname"><br><br>
            <label for="lname">Last name:</label>
            <input type="text" id="lname" name="lname"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
            <label for="birthday">Birthday:</label>
            <input type="date" id="birthday" name="birthday"><br><br>
            <input type="submit" value="Submit">
        </fieldset>
    </form>
</body>
</html>
```

### Forms Input Types
1. Button - This defines a button on your html page
* Examples : `<input type="button" onclick="alert(hello world!)" value="click me">`
2. Password - This defines a password field and the input is not shown as text.
* Examples : `<input type="password" id="pwd" name="pwd">`
3. Submit - This defines a button for submitting form data, to a form handler.
* Examples : `<input type="submit" value="submit">`
4. Reset - This will reset all the values to thier default values.
* Examples : `<input type="reset">`
5. Radio - This Allows user to select only one of a limited number of choices. 
* Examples : `<input type="radio" name="fav language" value="html">`
             `<input type="css" name="fav language" value="CSS">`
6. Checkbox - Lets the user to select 0 or more options of a limited number of choices.


### HTML Graphics 
#### Canvas
* canvas element is used to draw graphic on a webpage. The graphic to the left with canvas tag it shows 4 elements.
    1. Gradient Rectangle
    2. Mulitcolor Rectangle
    3. Multicolor Text

* The canvas element is only a container for graphics. You must use several methods for drawings paths, boxes, circles, text and adding images.
* Example : 
```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>
    <canvas id="MyCanvas" width="200" height="100" style="border: solid red;">Your browser doesn't support canvas</canvas>
</body>
</html>
```

* getElementById is a method to return element with a specified value, returns null is an element does not exist.
* It us one of the most common method in html dom, it is used almost everytime you  want to read all headed html element.
* Similarly we have other getElementBy(name, classname, tagname)


```html
<!DOCTYPE html>
<html>
<head>
</head>
<body>
    <canvas id="MyCanvas" width="200" height="100" style="border: solid red;">Your browser doesn't support canvas</canvas>
    <script type="text/javascript">
        var c = document.getElementById('myCanvas');
        var ctx = c.getContext("2d");
        ctx.moveTo(0, 0);
        ctx.lineTo(200, 100);
        ctx.stroke();
    </script>
</body>
</html>
```
