# README

## This is Markdown

And it is super simple!

## HTML

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Developer's Syntax</title>
  </head>
  <body>
    <p>Hello world!</p>

    <form
      class="Form"
      action="./"
      method="post"
    >
      <label
        for="name"
      >Your name</label>
      <input
        id="name"
        type="text"
        name="newsletter"
      />
      <label
        for="email"
      >Your email</label>
      <input
        id="email"
        type="email"
        name="newsletter"
      />
      <button
        id="Submit__Newsletter"
        type="submit"
      >Sign-up for the newsletter!</button>
    </form>
  </body>
</html>
```

## CSS

```css
:root {
  --color-primary: #bad;
}

@media screen and (max-width: 20em) {
  body {
    font-size: 1.25em;
    color: var(--color-primary);
    background-color: white;
    unknown: property;
  }
}
```

## JavaScript

```javascript
import Component, { utilityFn, html } from '@awesome/core';

class FormComponent extends Component {
  constructor(super) {
    super();
  }

  static props = {};

  render(props, context) {
    return html`
      <form>
        ${ props.children }
        <Component />
      </form>
    `;
  }
}

function someFn(param) {

  if (param === true) {
    return undefined;
  }

  for (var i = 0; i < param.items.length; i++) {
    param.items[i];
  }

  return param;
}

someFn('yolo');

```

## JSON

```json
{
  "stringKey": "value",
  "booleanKey": true,
  "nullKey": null,
  "arrayKey": [
    "value 1",
    {
      "key": "value"
    },
    ["arrayInArray"]
  ],
  "objectKey": {
    "key": "value"
  }
}
```
