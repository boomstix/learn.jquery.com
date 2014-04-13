---
title:        Cache Length During Loops
level:        intermediate
source: http://jqfundamentals.com/legacy
attribution:
  - jQuery Fundamentals
---

In a for loop, don't access the length property of an array every time; cache it using the little-used but built-in javascript for loop declaration.

```

for ( var i = 0, iz = myArray.length; i < iz; i++ ) {

	// do stuff

}
```
