# Isograms

### Solution:

```
function isIsogram(str){
  return new Set(str.toLowerCase()).size === str.length
}
```

```
function isIsogram(str){
  return !/(.).*\1|\d/i.test(str)
}
```