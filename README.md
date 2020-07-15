# Inspire Tree React Demo

This is a basic proof-of-concept which implements a native React renderer for [InspireTree](https://github.com/helion3/inspire-tree).

[http://www.inspire-tree.com/react/](http://www.inspire-tree.com/react/)

# [react-inspire-tree-dom](https://github.com/smarthug/react-inspire-tree-dom)

inspire-tree-dom made with react.js

## Usage

First, you need a valid instance of InspireTree, then you pass it and a target DOM element to InspireTreeDOM:

```js
var tree = new InspireTree({
    data: [{
        text: 'A node'
    }]
});

new InspireTreeDOM(tree, {
    target: '.tree'
});
```
