# Smart Focus Ring

Hides the CSS focus ring by default and adds a `user-is-tabbing` class to the body when a user hits the tab key. This shows a focus ring on form elements like buttons, fields, textareas and selects.

## Example

If you focus on the button via mouse, you won't see a focus outline. If you interact via keyboard, you will. 🎉

<img src="http://i.imgur.com/8zVT8We.gif" alt="Button Outline Demo" style="outline: 2px solid #c7bfc9" />

## Usage

Install the package

```bash
$ npm i smart-focus-ring
```

Import it into your project and add this JavaScript.

```javascript
import './node_modules/smart-focus-ring/lib/styles.css';
import smartFocusRing from 'smart-focus-ring';
smartFocusRing();
```

## Credit

Based on David Gilbertson's [Removing that ugly :focus ring (and keeping it too)](https://medium.com/hackernoon/removing-that-ugly-focus-ring-and-keeping-it-too-6c8727fefcd2).