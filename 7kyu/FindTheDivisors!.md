# Find the divisors!

### Solution:

```
function divisors(integer) {
  let div = []
  for (let i = 2; i < integer; i++){
    if (integer % i == 0) {
      div.push(i)
    }
  }
  return div.length === 0 ? `${integer} is prime` : div 
};
```