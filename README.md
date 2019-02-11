### picturefill
---
https://github.com/scottjehl/picturefill

```js
document.createElement("picture");

picturefill([
  elements: [ document.getElementById( "myImg" ) ]
]);

picturefill([
reevaluate: true,
  elements: [ document.getElementById( "myImg" ) ]
]);

window.picturefillCFG = window.picturefillCFG || [];
picturefillCFG.push([ "algorithm", "saveData" ]);
```

```
<img
  sizes="(min-width: 40em) 80vm, 100vm"
  srcset="examples/images/medium.jpg 375w,
          examples/images/large.jpg 480w,
          examples/images/extralarge.jpg 768w"
  alt="...">
```

```
```

