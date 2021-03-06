# jsblocks [![Build Status](https://travis-ci.org/astoilkov/jsblocks.svg?branch=master)](https://travis-ci.org/astoilkov/jsblocks)

Better MV-ish Framework

From simple user interfaces to complex single-page applications using faster, server-side rendered and easy to learn framework.

[[ official website ]](http://jsblocks.com)

### Discussion at Reddit

[jsblocks - faster than AngularJS and ReactJS. Better MV-ish Framework. Oh yeah!](https://www.reddit.com/r/javascript/comments/33l327/jsblocks_faster_than_angularjs_and_reactjs_better/)

### Features

 * [Server-side rendering](http://jsblocks.com/learn/introduction-why-jsblocks#server-side-rendering)
 * [Debugging experience](http://jsblocks.com/learn/introduction-why-jsblocks#debugging-experience)
 * [Faster](http://jsblocks.com/#performance)
 * [MV-ish](http://jsblocks.com/learn/introduction-why-jsblocks#mv-ish)
 * [Modular](http://jsblocks.com/learn/introduction-why-jsblocks#modular)
 * [Built-in utility library](http://jsblocks.com/learn/introduction-why-jsblocks#built-in-utility-library)
 * [Forward thinking](http://jsblocks.com/learn/introduction-why-jsblocks#forward-thinking)
 * [... and many more](http://jsblocks.com/learn/introduction-why-jsblocks#feature-rich)

### Getting started

Just copy and paste the code below for your first jsblocks application.
Continue with the [documentation](http://jsblocks.com/learn)
and the [jsblocks starter template project](https://github.com/astoilkov/jsblocks-seed)

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="http://jsblocks.com/jsblocks/blocks.js"></script>
    <script>
      blocks.query({
        name: blocks.observable()
      });
    </script>
  </head>
  <body>
    Name:
    <input data-query="val(name)" placeholder="Enter your name here" />
    <hr />
    <h1>Hello {{name}}!</h1>
  </body>
</html>
```

### Example projects
 * [TodoMVC](https://github.com/astoilkov/jsblocks-todomvc)
 * [E-shopping](https://github.com/astoilkov/jsblocks-shopping-example)
