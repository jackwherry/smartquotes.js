smartquotes.js
==============

Smart quotes are smart typography, and now it’s just a ’script away.

This is a fork of https://github.com/kellym/smartquotes.js adapted to turn `---` into —. That's all. You can see it in action at https://snazz.xyz.

## Installation

This version of smartquotes.js is meant to be used in-browser:

```html
<script src="smartquotes.js"></script>
<script>smartquotes()</script>
```

Get the file from the `dist/` directory in this repo. 

Make it look like this if you want it to constantly listen for additional changes:
```html
<script src="smartquotes.js"></script>
<script>smartquotes().listen()</script>
```

I currently ignore unit testing (unlike the [parent repo](https://github.com/kellym/smartquotes.js)) because my changes are very small. But if you want to add another conversion, just run `npm run build` for webpack to make you a finished build. If npm screams at you about security vulnerabilities, ignore it and move on. The webpack-generated code is not affected by any of them. 
