# javascript-interesting-features
A list of interesting features I found in javascript. A lot of them are probably deprecated, but we wilding here (just like javascript).

-------

- Labeled statements
- Generators
- Object.defineProperty
  - Setters && Getters
- ArrayBuffer
- Proxies
  - Handling method calls that don't exist, like with PHP's __call magic method
  - https://stackoverflow.com/questions/59390026/how-to-use-es6-proxy-in-typescript
- DOM Stuff (watch this [Building Alpine.js course](https://laracasts.com/series/building-alpinejs) to see some cool stuff)
  - Navigation
    - element.nextElementSibling (and previous) gives null if it doesn't find any
  - Attributes
    - You can set any custom attributes, then deal with them using: hasAttribute, getAttribute and setAttribute
- `with` statement: https://developer.mozilla.org/en/docs/Web/JavaScript/Reference/Statements/with
