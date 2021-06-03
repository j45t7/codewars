# Mumbling

### Solution:

```
function accum(s) {
  // your code
  let arr = s.split('')
  let str = ''
  for (let i =0; i < arr.length; i++){
    str += `${arr[i].toUpperCase()}${arr[i].toLowerCase().repeat(i)}-`
  }
  return str.slice(0, -1)
}
```

```
function accum(s) {
  // your code
  return s.split('').map((letter, i) => (`${letter.toUpperCase()}${letter.toLowerCase().repeat(i)}`)).join('-')
}
```