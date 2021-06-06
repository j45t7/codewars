# Descending Order

### Solution:

```
function descendingOrder(n){
   return +n.toString().split('').sort().reverse().join('')
}
```
```
function descendingOrder(n){
  return  +n.toString().split('').sort((a, b) => (a > b ? -1 : 1)).join('')
}
```
