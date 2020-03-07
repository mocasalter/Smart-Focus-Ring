# Smart Focus Ring

Hides the CSS focus ring by default and adds a `user-is-tabbing` class to the body when a user hits the tab key. This shows a focus ring on form elements like buttons, fields, textareas and selects.

## Usage

Install the package

```bash
$ npm i smart-focus-ring
```

Import it into your project and add this JavaScript.

```javascript
import smartFocusRing from 'smart-focus-ring';
smartFocusRing();
```

## Credit

Based on David Gilbertson's [Removing that ugly :focus ring (and keeping it too)](https://medium.com/hackernoon/removing-that-ugly-focus-ring-and-keeping-it-too-6c8727fefcd2).