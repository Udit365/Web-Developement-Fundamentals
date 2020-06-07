# HTML5 Basics

There are several new features present in HTML5.

The first and foremost of them is `<!DOCTYPE HTML>`.

Also, the character encoding (charset) declaration became more simplified as follows :

```html
<meta charset="UTF-8" />
```

> **_Note :_** The default character encoding in HTML5 is UTF-8

#### New Elements in HTML5

Some of the new elements introduced in HTML5 are :

- `<article>` tags
- `<aside>` tags
- `<audio>` tags
- `<video>` tags
- `<canvas>` tags
- `<datalist>` tags
- `<details>` tags
- `<embed>` tags
- `<header>` tags
- `<footer>` tags
- `<nav>` tags
- `<section>` tags
- `<progress>` tags
- `<output>` tags

and so on.

Other exciting things in HTML5 includes :

- Forms (Web Forms 2.0)
- Integrated API

#### Forms in HTML5

The web forms 2.0 specifications allows for the creation of more powerful forms and more compelling user experiences.

_Date Pickers, Color Pickers & Numeric stepper controls_ have been added.

The input field types in HTML5 now includes _email, search & URL_

`PUT` and `DELETE` form methods are now supported too.

## Content Models

HTML5 introduces _seven primary content models_ as follows :

1. Metadata
2. Embedded
3. Interactive
4. Heading
5. Phrasing
6. Flow
7. Sectioning

The content models are designed to make the mark-up structure more meaningful both for the browser and the web designer.

The same element can be in multiple content model as well.

### Metadata

This is the Content that sets up the presentation or behavior of the rest of the content.

These elements are found in the head of the document.

Elements/Tags includes are :
`<base>`,`<link>`,`<meta>`,`<script>`,`<style>`, `<title>`, `<noscript>`

### Embedded

This is the Content that imports other resources into the document.

Elements/Tags includes are :
`<audio>`,`<video>`,`<canvas>`,`<iframe>`,`<img>`, `<object>`, `<svg>`, `<math>`

### Interactive

This is the Content that specifically intended for user interaction.

Elements/Tags includes are :
`<a>`,`<video>`,`<audio>`,`<button>`,`<details>`, `<embed>`, `<iframe>`, `<img>`,
`<input>`,`<label>`, `<object>`,`<select>`,`<textarea>`

### Heading

This is the Content that defines a section header.

Elements/Tags includes are :
`<h1>`,`<h2>`,`<h3>`,`<h4>`,`<h5>`,`<h6>`,`<hgroup>`

### Phrasing

This is the Content that has a number of inline level elements in common with HTML4.

Elements/Tags includes are :
`<img>`,`<span>`,`<strong>`,`<label>`,`<br/>`,`<small>`,`<sub>` etc.

### Flow

This is the Content that has majority of HTML5 elements that would be included in the normal flow of the document.

Elements/Tags includes are :
All the content model elements except some of elements from "_Metadata_" content model.

### Sectioning

This is the Content that defines the scope of headings, content, navigation, and footers.

Elements/Tags includes are :
`<article>`,`<aside>`,`<nav>`,`<section>`

The following image shows, how the various content models overlap in certain areas, depending on their use cases :

## The HTML5 Page Structure

A basic HTML5 page structure is more or, less looks like this one :
