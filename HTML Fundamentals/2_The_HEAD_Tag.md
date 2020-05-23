# The `<head>` Tag

Some of the very important information about the web page such as title, description, content type etc. are placed within the opening and closing `<head>` tag.

A basic `<head>` tag looks as follows :

```HTML
<head>
    <title> My First Web Page </title>
    <meta name="description" content="Page Description Here"/>
    <meta http-equiv="Content-Type" content="text/html"; charset="UTF-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>

    <style type="text/css">
        Body {
            color: red;
        }

    </style>

    <script>
        function myFunction() {
            var x = document.getElementById("fname");
            x.value = x.value.toUpperCase();
        }
    </script>
</head>
```

In the above `<head>` tag we have the following sub-tags :

- `<title>` Tag
- `<meta>` Tag
- `<style>` Tag
- `<script>` Tag

## The `<title>` Tag

The `<title>` tag also has a closing tag as `</title>`.

The web page name is enclosed within this tag and it can be seen as the tab name in the web browser.

## The `<meta/>` Tag

This tag don't have a closing tag but, it communicates with the web browser and with the search engine to provide valuable information about the webpage.

`<meta/>` tag can be of various forms as discussed below :

### Page Description

The following `<meta/>` tag gives the description about the web page and it is primarily intended for the search engines.

```HTML
  <meta name="short description" content="long description"/>
```

When we search something on the search engine then, we can see this page description in the related search results as follows :

<img src="..\Images\meta_name_tag.jpg" width="500">

If the page description is not provided in this manner then the search engine will automatically generate one based on the content of the page.

### Defining Character Set

The following `<meta/>` tag defines the character set to be used in the web page and for most of the cases, it is `UTF-8`.

```HTML
<meta http-equiv="Content-Type" content="text/html"; charset="UTF-8"/>
```
### Web Page Responsive

The following `<meta/>` tag makes the web page responsive for different screen sizes and devices.

```HTML
<meta name="viewport" content="width=device-width, initial-scale=1"/>
```
The *viewport* defines the user's visible area of the webpage and it varies depending upon the user's device.

This metatag instructs the browser on how to control the dimension of the webpage.

The command `width=device-width` instructs the browser to have a responsive width based on the viewing device and `initial-scale=1` sets the initial zoom level (i.e., when the web page is first loaded by the browser).

## The `<style>` Tag ✨

The `<style>` tag also has a closing tag as `</style>`.

The codes enclosed between the `<style>` tags are referred as the *style rules* and they define the presentation of visual elements on an HTML page.

The *style rules* are nothing but the *CSS (Cascading Style Sheet)* rules that can beautify almost everything on the web page.

For example; the following CSS code changes the colour of all the texts enclosed between the `<body>` tags to red.

```HTML
<style type="text/css">
    Body {
        color: red;
    }

</style>
```

## The `<script>` Tag 📜

The `<script>` tag also has a closing tag as `</script>`.

The codes enclosed between the `<script>` tags are nothing but the *Javascript* codes that makes the web page dynamic.

For example; the following JS function capitalizes each letter of user input in the input box.


```HTML
<script>
    function myFunction() {
        var x = document.getElementById("fname");
        x.value = x.value.toUpperCase();
    }
</script>
```
