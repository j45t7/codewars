# Find the next perfect square!

### Solution:

```
function findNextSquare(sq) {
  // Return the next square if sq is a perfect square, -1 otherwise
  return Number.isInteger(Math.sqrt(sq)) ? Math.pow((Math.sqrt(sq)+1), 2) : -1
}
```

```
function findNextSquare(sq) {
  // Return the next square if sq is a perfect square, -1 otherwise
  return Math.sqrt(sq)% 1 === 0 ? (Math.sqrt(sq) + 1) ** 2 : -1
}
```