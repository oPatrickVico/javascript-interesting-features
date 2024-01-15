# javascript-interesting-features
A list of interesting features I found in javascript. A lot of them are probably deprecated, but we wilding here (just like javascript).

-------

# Work in progress!

- Labeled statements
- Generators
  - [Use case of generators, plus return method intro](https://github.com/tc39/proposal-explicit-resource-management#ecmascript-explicit-resource-management)
- [Mutation Observers](https://developer.mozilla.org/en-US/docs/Web/API/MutationObserver)
  - Useful if you are using data attributes, as well as modifying children of an element
- Object.defineProperty
  - Setters && Getters
- Proxies
  - Handling method calls that don't exist, like with PHP's __call magic method
  - Adding functionality when updating class attributes, like setters and getters definitions, but better in certain regards
  - https://stackoverflow.com/questions/59390026/how-to-use-es6-proxy-in-typescript
- Proxies Vs Object.defineProperty
- DOM Stuff (watch this [Building Alpine.js course](https://laracasts.com/series/building-alpinejs) to see some cool stuff)
  - Navigation
    - element.nextElementSibling (and previous) gives null if it doesn't find any
  - Attributes
    - You can set any custom attributes, then deal with them using: hasAttribute, getAttribute and setAttribute
- `with` statement: https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Statements/with
- ArrayBuffer
- addEventListeners vs onevent event settings
  - addEventListeners and declared functions, function expressions and arrow functions
- Tagged Templates
  - [this article](https://www.strictmode.io/articles/javascript-tagged-templates) teaches everything you need to know
- Web Components:
  - `<template>` tag
  - Custom Elements
  - Shadow root
- Symbol
  - Symbol.iterator: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol/iterator
