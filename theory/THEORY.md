# Theory Homework - Lesson 1 (Inception)

## What is Emmet?

Emmet is a tool used to autocomplete HTML tags. It also provides a shortcut command system to generate HTML commands easily.

## Difference between a Library and a Framework.

Libraries are simple bundles of reusable code which are used to for making repetative tasks easier. They are like plug and play codes for us. We can use libraries in any project.

Frameworks are structured libraries which are used to structure and organize code. The main difference between a library and framework is that frameworks are opiniated, ie, they have a predifined set of rules and conventions that the developer has to follow. This allows the dev to focus on building the functionalities of the app rather than worrying about low level stuff like folder structure, and performing common tasks such as module bundling, task runners etc.

## What is CDN?

CDN stands for Content Delivery Network. It is like a network of servers. How fast we can access a web app or a website online directly depends on how far the server is from us. So, CDN distributes the files in a network of servers and when user tries to access it, the closest server is chosen.

## Why is React known as React?

One of the key ideas behind React is the concept of "Reactivity", which means that UI should only load required parts of a page rather than loading the entire page.

## What is crossorigin?

`crossorigin` attribrute is used to indicate whether or not a script can make requests to other domains or not.

It takes in following values - `anonymous` which means that script can make requests to another domain but is not allowed to share credentials like cookies or HTTP authentication.

`use-credentials` allows to share credentials.

The default value when no value is specified is `anonymous`.

This is often used in conjuction with `CORS` which allows a server to specify which domains are allowed to make requests to it.

## What is the difference between React and ReactDOM?

`React` is the library used to create reusable UI components.

`ReactDOM` is used to render those components in the website. 

Similar to `ReactDOM`, `react-native` is a library used to render react components for mobile applications.

## What is the difference between `react.development.js` and `react.production.js` ?

`react.development.js` creates human readable code.

`react.production.js` creates minified code.

## What is `async` and `defer`?

`async` is used to load a script asynchronously,this means that the script loads in background while the page is loading and runs when it's available.

`defer` also loads in background but only runs when the entire HTML document is loaded.
