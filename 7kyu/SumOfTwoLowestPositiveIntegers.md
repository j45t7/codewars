# Sum of two lowest positive integers

### Solution:

```
function sumTwoSmallestNumbers(numbers) {  
  let sorted = numbers.sort((a, b) => a -b)
  return sorted[0] + sorted[1]
}
```

```
function sumTwoSmallestNumbers(numbers) {  
  let [a, b] = numbers.sort((a, b) => a -b)
  return a + b
}
```

```
function sumTwoSmallestNumbers(numbers) {  
  return numbers.sort((a, b) => a -b).slice(0, 2).reduce((a, b) => a + b)
}
```