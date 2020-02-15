<json>
{
  "title": "Base64 Sifreleme",
  "date": "6/11/2019",
  "tags": ["hello"],
  "imageUrl": "https://camo.githubusercontent.com/769d609affb3c9c805430f96f97c82bf9fa57e6d/68747470733a2f2f692e696d6775722e636f6d2f6273694579694d2e706e67"
}
</json>

# Base64 Chipper

# Live demo

Changes are automatically rendered as you type.

## Table of Contents

- Implements [GitHub Flavored Markdown](https://github.github.com/gfm/)
- Renders actual, "native" React DOM elements
- Allows you to escape or skip HTML (try toggling the checkboxes above)
- If you escape or skip the HTML, no `dangerouslySetInnerHTML` is used! Yay!

## HTML block below

<blockquote>
  This blockquote will change based on the HTML settings above.
</blockquote>

## How about some code?

```js
var React = require("react");
var Markdown = require("react-markdown");

React.render(
  <Markdown source="# Your markdown here" />,
  document.getElementById("content")
);
```

Pretty neat, eh?

## Tables?

| Feature   | Support |
| --------- | ------- |
| tables    | ✔       |
| alignment | ✔       |
| wewt      | ✔       |

## More info?

Read usage information and more on [GitHub](//github.com/rexxars/react-markdown)

---

A component by [Espen Hovlandsdal](https://espen.codes/)
