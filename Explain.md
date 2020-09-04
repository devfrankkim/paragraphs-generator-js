
### addEventListener('submit') -> refreshing the webpage by default -> event.preventDefault()
- submit has the default behavior
- the page will refresh by default behavior
- so the logic will go away

```js
form.addEventListener("submit", (e) => {
  console.log("hello");
  e.preventDefault();
  console.log("hello");
});
```
### HTML: input.value  -> 'String'

```
  input.value;
  -------- 
  input.value is "String"
  the value that you are getting back is 'String'
  even if HTML said the type is number
  -----
  console.log(typeof value)
```

### Number()
```
var a = false;
Number(a); // 0
var b;
Number(b) // NaN
var c = '  ';
Number(c) // 0
```

### isNaN('a') 
```js
isNaN('a') // true
isNaN('1' + '1') // false
isNaN(1)
```