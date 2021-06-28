# Sum of Digits / Digital Root

### Solution:

```
function digital_root(n) {
  if (n < 10) return n
  return digital_root(
    n.toString().split('').map(num => Number(num)).reduce((a,b) => {
  return a + b},0)
  )
}
```