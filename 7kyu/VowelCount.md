# Vowel Count

### Solution:

```
function getCount(str) {
return str.match(/[aiueo]/gi) === null ? 0 : str.match(/[aiueo]/gi).length
}
```