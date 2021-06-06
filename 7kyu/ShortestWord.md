# Shortest Word

### Solution:

```
function findShort(s){
   return Math.min(...s.split(' ').map(word => word.length))
}
```