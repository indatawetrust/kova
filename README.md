# kova
change the specified key values

```js
const object = {
  a: {
    b: {
      c: {
        d: 'CHANGE ME'
      }
    },
    e: 'CHANGE ME'
  }
}

console.log(kova(object, 'CHANGE ME', 'CHANGED'))

{
  a: {
    b: {
      c: {
        d: 'CHANGED'
      }
    },
    e: 'CHANGED'
  }
}
```
