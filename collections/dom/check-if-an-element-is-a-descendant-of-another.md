~~~ javascript
const isDescendant = (child, parent) => parent.contains(child);

// Or
const isDescendant = (child, parent) => child?.parentNode === parent;
~~~
