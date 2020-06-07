# Types of Element

There are basically, two types of elements present in HTML, i.e.

- Inline Elements
- Block Elements

## Inline Elements

These elements are normally displayed without any line breaks.

**_For Example :_**

The tags like `<b>`,`<a>`,`<i>`,`<img>`,`<span>`,`<font>`,etc. comes under the inline elements in HTML.

So, if we start a `<b>` tag just after the `<a>` tag then we will not see the contents of `<b>` tag in the next line but, it will show up in the same line.

### The `<span>` Element

The `<span>` element is an inline element that is often used as a container for some text.

When used together with CSS, this `<span>` element can be used to style parts of the text

But, in HTML5, the `<span>` element is almost replaced by the `<font>` tag that works exactly as the `<span>`.

```html
Some <span style="color:red">Important</span> Message
```

## Block Elements

The block level elements will start from a new line.

**_For Example :_**

The tags like `<h1>`,`<form>`,`<li>`,`<ol>`,`<ul>`,`<p>`,`<table>`,`<div>`,`<article>`,etc. comes under the block elements in HTML.

So, if we start a paragraph with `<p>` tag or, a header with `<h1>`tag then, we can see even without providing any of the line breaks tag like `<br/>` tags, the content under block level element will start showing up in the next line.

### The `<div>` Element

It is a block level element that is often used as a container for other HTML elements.

When used together with CSS, this `<div>` element can be used to style blocks of content.

But, in HTML5, the `<div>` element is almost replaced by the `<article>` tag that works exactly as the `<div>`.

```html
<div style="background-color:green; color:white; padding:20px">
  <h1>This is a header</h1>
  <p>This is a paragraph</p>
  <b>This is a strong text</b>
  <p>Here goes another paragraph</p>
</div>
```

## Special Cases

There are some HTML elements that can either be used as inline or, block elements.

Those elements are :

- `<applet>`: Embedded Java applet
- `<iframe>`: Inline frame
- `<ins>`: Inserted text
- `<map>`: Image map
- `<object>`: Embedded object
- `<script>`: Scripts withing HTML documents

We can insert multiple inline elements within the block element but the reverse is not true.
