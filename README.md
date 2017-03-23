Reactor
---

A react starter project

Setup
---
 
```
npm install
```

Babel
---

Transforms ES6 js to ES5 js for current browsers. Used to convert JSX syntax.
 
 Webpack
 ---
 
 Bundles and minify js files, with babel, converts ES7/ES6 to ES5.
 
 Webpack config breakdown:
 
 - context: Path to client side js folder
 - entry: Application entry
 - output: Output folder/ file for bundled js
 - loaders: (Rules): specify how each file should be processed before being bundled.
 - resolve: Path to imported and required packages
 