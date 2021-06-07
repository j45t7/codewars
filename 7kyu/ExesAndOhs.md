# Exes and Ohs

### Solution:

```
function XO(str) {
 let word = str.toLowerCase().split('')
 return word.filter(letter => letter === 'x').length  === word.filter(letter => letter === 'o').length
}
```