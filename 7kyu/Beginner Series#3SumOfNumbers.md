# Beginner Series #3 Sum of Numbers

### Solution:

```
function getSum( a,b )
{
  let min = a < b ? a : b
  let max = a > b ? a : b
  let sum = (min, max) => {
    let n = (max - min + 1);
    let sum = n * (min + max) / 2; 
    return sum;
  }
  return a === b ? b : sum(min, max)
}
```

```
function getSum( a,b )
{
   return (Math.abs(a-b) + 1) * (a + b)/2
}
```

```
function getSum( a,b )
{
  let min = Math.min(a,b)
  let max = Math.max(a,b)
  return  (max - min + 1) * (min + max) / 2; 
}
```