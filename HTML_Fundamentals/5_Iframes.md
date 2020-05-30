# Iframes

Iframes are nothing but the HTML documents embedded within another HTML document.

Iframes are commonly used to insert content from another source into a webpage.

The `<iframe>` tags are used to insert an "_Iframe_"

The following "_Iframe_" tags renders bing.com site into the webpage that covers the full width (`width="100%"`) and has a height of 400 pixels (height="400").

In case, the browser doesn't supports the `<iframe>` tags, a message will be shown to them (Message inside of the `<p>` tags)

```html
<iframe src="https://www.bing.com/" width="100%" height="400">
  <p>Your browser don't support iframes.</p>
</iframe>
```
