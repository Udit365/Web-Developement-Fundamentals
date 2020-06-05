# The `<body>` Tag

The `<body>` tags contains all sorts of visible texts, lists, images, links, tables etc. within it.

Separate tags and syntax exists to add all these visible elements inside the `<body>` tags.

Some of the basic operations performed within the `<body>` tags are :

1.  Sentence formatting
2.  Text formatting
3.  Adding Lists
4.  Adding & formatting Images
5.  Adding & formatting Videos
6.  Adding & formatting Links (Relative/Absolute)
7.  Adding Anchor tags
8.  Adding & formatting Tables

## Sentence Formatting

Sentence formatting includes :

-   Adding Paragraphs (With `<p>` tags)
-   Adding Line breaks (With `<br>` or, `<br/>` tag)
-   Adding blank spaces (With `&nbsp;` tag)
-   Adding horizontal line (With `<hr>` or, `<hr/>` tag)

### The `<p>` Tags

The `<p>` tags creates the paragraph spacing between the lines of text.

_For example :_

```HTML
<p>
  It was the hunter's first time outside the forest. He was surprised to see the roads, the cars, the tall buildings and crowd surrounding him.
</p>

<p>
  Now it was dark and they heard a scream of a woman. They all were shocked because as per their knowledge the village is too far away for any voice to reach the middle of the jungle.
</p>
```

### The `<br>` or, `<br/>` Tag

The `<br>`/`<br/>` tag don't have a closing tag and it simply breaks the line to start the next sentence on the next line.

Unlike the `<p>` tags, it don't creates a large spacing but, just creates a new line for the sentence.

_For example :_

```HTML
It was another day in the city and the hunter is still clueless.<br>
The door bell rang and someone outside started speaking in a gentle voice.<br/>
The hunter was afraid and asked "Who are you ?"
```

### The `&nbsp;` Tag

HTML ignores the blank spaces between sentences and this is popularly known as the "_white space collapsing_" property.

So, spaces created by the _Tab Key, Enter Key_ or, _Space bar_ is basically ignored by HTML.

Therefore, to add empty spaces between sentences, we can use the keyword `&nbsp;` between two sentences.

`&nbsp;` stands for "_Non-Breaking Spaces_" and one such tag creates a single space (equivalent of tapping the _space bar_ once).

If we want to have blank spaces equivalent of pressing the _Tab key_ once then, we have to write `&nbsp;` for four times.

### The `<hr>` or, `<hr/>` Tag

The `<hr>`/`<hr/>` simply adds a horizontal line in the webpage :

```html
Steve was born in Tokyo, Japan in 1950. He moved to London with his
parents when he was 5 years old.
<hr>
Steve started school there and his father
began work at the hospital. His mother was a house wife and he had four
brothers.
<hr/>
```

_For Example :_

```HTML
This marks the end of hunter's life. Hunter died as he can't cooperate with the city lifestyle but,what message he gave us is worth remembering.
&nbsp; &nbsp; &nbsp; &nbsp;  It was a new morning and the hunter found himself in his cottage but, now it looks a little different. There were flowers everywhere and birds were chippering outside.
```

## Text Formatting

The text formatting includes :

-   Adding Headlines (With `<h1>,<h2>,..,<h6>` tags)
-   Making the fonts bold (With `<strong>` or, `<b>` tags)
-   Making the fonts italic (With `<em>` or, `<i>` tags)
-   Making the fonts underlined (With `<u>` or, `<ins>` tags)
-   Making the fonts strike-through (With `<strike>` or, `<del>` tags)
-   Making the fonts big & small (With `<big>` and `<small>` tags)
-   Adding subscripts & superscripts (With `<sub>` and `<sup>`)
-   Adding in-line text formatting (With `<font>` tags)

### Header Tags

The header tags are a set of six similar tabs that are used to add headers & sub-headers.

Each header tag has its corresponding ending tag and texts enclosed between these tags behave as a title for the document.

The six different header tags are as follows (in descending order of header size) :

`<h1> </h1>` : Largest size
`<h2> </h2>` : Smaller size than `<h1>` tags
`<h3> </h3>` : Smaller size than `<h2>` tags
`<h4> </h4>` : Smaller size than `<h3>` tags
`<h5> </h5>` : Smaller size than `<h4>` tags
`<h6> </h6>` : Smallest size

_For Example :_

```HTML
<h1> Header 1 </h1>
<h2> Header 1 </h2>
<h3> Header 1 </h3>
<h4> Header 1 </h4>
<h5> Header 1 </h5>
<h6> Header 1 </h6>
```

### The `<strong>` or, `<b>` Tags

To make a text bold, we need to enclose that within the `<strong>` or, `<b>` tags as follows :

_For Example :_

```HTML
The key character of the story is <strong> hunter </strong>.
```

or,

```HTML
The key character of the story is <b> hunter </b>.
```

### The `<em>` or, `<i>` Tags

To make a text italics, we need to enclose that within the `<em>` or, `<i>` tags as follows :

_For Example :_

```HTML
Let's make this word <em> italics </em>.
```

or,

```HTML
Let's make this word <i> italics </i>.
```

### The `<u>` or, `<ins>` Tags

To underline a text, we need to enclose it within the `<u>` or, `<ins>` tags as follows :

_For Example :_

```HTML
This is something very <u> important </u>
```

or,

```HTML
This is something very <ins> important </ins>
```

### The `<strike>` or, `<del>` Tags

To strikethrough a text, we need to enclose it within the `<strike>` or, `<del>` tags as follows :

_For Example :_

```HTML
This task is completed so need to <strike> strikethrough </strike> this.
```

or,

```HTML
This task is completed so need to <del> strikethrough </del> this.
```

To Make a word bold, underlined and italics at the same time, we can enclose it within the respective three tags irrespective of any order but, the respective closing tags must follow the order of the opening tags.

_For Example :_

```HTML
Let's make this <em><strong><u> bold, italics & underlined  </em></strong></u>
```

### The `<big>` and `<small>` tags

To make the font bigger relative to other texts, we can use the `<big>` tags :

```html
This font is <big>BIG</big>
```

Similarly, `<small>` tags are used to make the test smaller relative to other texts :

```html
This font is <small>small</small>
```

### The `<sub>` and `<sup>` tags

`<sub>` tags can be used to add subscripts within the texts :

```html
This chemical formula for water is H<sub>2</sub>O
```

Similarly, `<sup>` tags can be used to add superscripts within the texts :

```html
This Coca-Cola trademark is written as CC<sup>TM</TM>
```

### Inline Text Formatting with `<font>` tags

A much flexible way of text formatting is inline text formatting.

_For Example :_

with the following HTML syntax, we have made :

-   Font type : Arial
-   Font size : 24
-   Font colour : Blue

```HTML
<font face = "arial"  size = "22" color = "blue"> This is the text </font>
```

## Creating Lists

List can be of two types, such as :

1.  Unordered List
2.  Ordered List

### Unordered List

The items in an unordered lists are in no particular order. To create an unordered list in HTML, we have to follow the syntactical rule of the following example.

_For Example :_

To create an unordered list of top BI tools :

```HTML
<ul>

  <li> Power BI </li>
  <li> Tableau </li>
  <li> Qlik </li>
  <li> MicroStrategy </li>

</ul>
```

### Ordered List

The items in an ordered lists are in a particular order and they are identifiable by a sequential order of numbers. To create an ordered list in HTML, we have to follow the syntactical rule of the following example.

_For Example :_

Listing out favourite subjects in descending order :

```HTML
<ol>

  <li> Data Science </li>
  <li> Data Analytics </li>
  <li> Statistics </li>
  <li> Graphic Design </li>
  <li> Frontend Development </li>

</ol>
```

## Adding Images

The `<img>` tag is used to add images in the web page. We need to follow the below syntactical rule to add an image :

```HTML
<img src= "Relative/Absolute image address">
```

The `src` tag takes up the image address for rendering. Similarly, we can control the width and height of the image by `width` and `height` tag as follows :

```HTML
<img src= "Relative/Absolute image address" width="500" height="500">
```

> If we don't provide the `height` tag then, the image will be auto-adjusted according to the width.

Similarly, we can add borders around the image with `border` attribute, as follows :

```html
<img src= "Relative/Absolute image address" width="500" height="500"border = "1">
```

## Embedding Videos

The `<video>` tags is used to embed any video on the web page.

```HTML
<video width = "100%" controls>

  <source src="Relative/Absolute video address" type="video/mp4">
  Your video doesn't support the video tag

</video>
```

By setting `width = "100%"`, we made the video element to cover the entire screen width of browser. So, we can tweak this percentage as per our convenience.

We can also specify the `width` in pixels, such as, `width = "500"` and in this case, the video element will have a constant width irrespective of the browser screen width.

The `controls` element adds the "_Play_" and "_Progress bar_" to the video and we can remove it if we need.

But, after removing the `controls` element, we need to add another element, i.e., `autoplay` otherwise, the video will not play.

> Note : `autoplay` doesn't support in most of the mobile devices like iPhone and iTab etc.

The `src` and `type` tag takes up the video address and video type respectively for rendering.

## Adding Links

The `<a>` tags are used to add links in the web page.

Links can be of two types :

-   Textual Links
-   Image Links

### Textual Links :

To add textual links in the web page, we can follow the syntactical rule given in this example :

_For Example :_

Adding a link for the Wikipedia page :

```HTML
<a href= "https://www.wikipedia.org/"> Wikipedia Page </a>
```

In the above example, we have added the link to the text "Wikipedia Page".

To open the link in a new tab (or, a new browser window), we need to add `target="_blank"` argument in the opening `<a>` tag, as follows :

```HTML
<a href= "https://www.wikipedia.org/" target="_blank"> Wikipedia Page </a>
```

### Image Links :

We can add links to the images as well, as follows :

```HTML
<a href="https://www.wikipedia.org/" target="_blank">
  <img src="https://tiny.cc/public/images/robot_small.png" width="150">
</a>
```

Through Image links, the user can navigate to the provided link by clicking on the image.

## Anchor Tags

Unlike the links; the anchor tags allow us to navigate to a specific portion of the content on the existing page.

**_For Example:_**<br>

In the following picture, we have the "_Article No._" as the bullet points by clicking which we can navigate to that specific article on the webpage.

<img src="../Images/article_tag.jpg" width=500>

To set-up such navigation, we have to use the `<a>` tags as follows on the "_Article Header_" :

```html
<h1>
  <a id="article1"> Article-1 </a>
</h1>
```

Similarly, we have to set-up the clickable link to the specific article on the bullet point names as follows :

```html
<li>
  <a href="#article1"> Article 1 </a>
</li>
```

The `#` symbol is used to tell the browser to search for `article1` in the same webpage.

## Adding Tables

The `<table>` tags are used to add tables in the web page.

We can add a table in the web page by following the syntactical approach given in the below example :

```HTML
<table width="50%" border="1" bordercolor="blue" cellspacing="2" cellpadding = "2">
  <tr>
    <td> Sports </td>
    <td> Responses </td>
  </tr>
  <tr>
    <td> Basketball </td>
    <td> 25 </td>
  </tr>
  <tr>
    <td> Baseball </td>
    <td> 28 </td>
  </tr>
</table>
```

-   `<tr>` tags add a row to the table
-   `<td>` tags add column to the table

The opening `<table>` tag also takes several attributes to format the table as well and they are as follows :

-   `width = 50%` : Table covers 50% of browser width, to have a fixed table width irrespective of any browser width, we can specify the pixels instead of percentages. For example : `width = "500"`

-   `border="1"` : Sets the border thickness, to have a table without any borders, we can set `border = "0"`.

-   `bordercolor="blue"` : Sets the color of the table border to "Blue".

-   `cellspacing="2"` : Sets the space between two consecutive cells to "2" pixels

-   `cellpadding = "2"` : Pads the number 2 pixels away from each side of its cell.

The below image illustrates the cell-spacing and cell-padding in a table :

<img src = "../Images/cell_spacing_and_padding.jpg">

### Nested Tables :

We can also create nested tables by adding the child-tables into the cells of parent table.

The width of the child table will always remain relative to its parent table only.

If the fixed width assigned to the child-table is greater than the fixed with assigned to the parent table then, the parent-table width becomes equal to the child-table width.

So, we can say, in no way, the child-table overflows out of the parent table.

The following example creates two side by side child tables :

```HTML
<table width="50%" border="1" bordercolor="red" cellspacing="2" cellpadding = "2">
  <tr>

    <td>
      <table width="100%" border="1" bordercolor="blue" cellspacing="2" cellpadding = "2">
        <tr>
          <td> Sports </td>
          <td> Responses </td>
        </tr>
        <tr>
          <td> Basketball </td>
          <td> 25 </td>
        </tr>
        <tr>
          <td> Baseball </td>
          <td> 28 </td>
        </tr>
      </table>
    </td>

    <td>
    <table width="100%" border="1" bordercolor="blue" cellspacing="2" cellpadding = "2">
      <tr>
        <td> Sports </td>
        <td> Responses </td>
      </tr>
      <tr>
        <td> Football </td>
        <td> 40 </td>
      </tr>
      <tr>
        <td> Cricket </td>
        <td> 45 </td>
      </tr>
    </table>
  </td>

  </tr>
</table>
```

### Merging Cells

We can merge the cells of a table by adding an attribute, `colspan = "no. of rows/columns to merge"` to the `<td>` tabs (for merging by columns) or, `<tr>`tabs (for merging by rows).

The following example, merges two side by side column headers of a `(3 x 2)` table :

```HTML
<table width="50%" border="1" bordercolor="black" cellspacing="2" cellpadding="2">
  <tr>
    <td colspan="2"> My Expenses </td>
  </tr>
  <tr>
    <td> January </td>
    <td> $500 </td>
  </tr>
  <tr>
    <td> February </td>
    <td> $200 </td>
  </tr>
  <tr>
    <td> March </td>
    <td> $300 </td>
  </tr>
  <tr>
    <td> Total </td>
    <td> $1000 </td>
  </tr>
</table>
```

### Text Wrapping in Cells

By default, the HTML tables wraps up the cell content if it is long enough to be accommodated within the specified cell width but; if we don't want to wrap our texts then, we can add an additional attribute, `nowrap` to do so.

In the following example, `nowrap` is applied to the column header :

```HTML
<table width="200" border="1" bordercolor="black" cellspacing="2" cellpadding="2">
  <tr>
    <td colspan="2" nowrap> My expenses in the 1st two motnths of Q1-2020 is as follows : </td>
  </tr>
  <tr>
    <td> January </td>
    <td> $500 </td>
  </tr>
  <tr>
    <td> February </td>
    <td> $200 </td>
  </tr>
</table>
```

> **_Note :_** `nowrap` attribute overwrites the specified table width.

### Text Alignments in Cells

The cell contents can be aligned to left, right, centre or, justify by using the following attributes :

-   `align = "right"`- For right alignment
-   `align = "left"` - For left alignment
-   `align = "center"` - For centre alignment

In the following example, the column headers and "Expenses" column ins centre aligned whereas, the "Month" column is left aligned :

```HTML
<table width="30%" border="1" bordercolor="black" cellspacing="2" cellpadding="2">
  <tr>
    <td align="center"> Month </td>
    <td align="center"> Expenses </td>
  </tr>
  <tr>
    <td align="left"> January </td>
    <td align="center"> $500 </td>
  </tr>
  <tr>
    <td align="left"> February </td>
    <td align="center"> $200 </td>
  </tr>
  <tr>
    <td align="left"> March </td>
    <td align="center"> $300 </td>
  </tr>
</table>
```

## Table Background

With the help of `background` attribute, we can set any image as the background of the whole table or, for some specific column/row/cell as well.

The following example shows, how to add an image as the table background :

```HTML
<table width="30%" border="1" background="Image URL">
  <tr>
    <td align="center"> Month </td>
    <td align="center"> Expenses </td>
  </tr>
  <tr>
    <td align="left"> January </td>
    <td align="center"> $500 </td>
  </tr>
  <tr>
    <td align="left"> February </td>
    <td align="center"> $200 </td>
  </tr>
  <tr>
    <td align="left"> March </td>
    <td align="center"> $300 </td>
  </tr>
</table>
```

similarly, we can set a color as the table background with the help of `bgcolor` attribute  as follows :

```HTML
<table width="30%" border="1" bgcolor="red">
  <tr background="Image URL">
    <td align="center"> Month </td>
    <td align="center"> Expenses </td>
  </tr>
  <tr>
    <td align="left"> January </td>
    <td align="center"> $500 </td>
  </tr>
  <tr>
    <td align="left"> February </td>
    <td align="center"> $200 </td>
  </tr>
  <tr>
    <td align="left"> March </td>
    <td align="center"> $300 </td>
  </tr>
</table>
```
