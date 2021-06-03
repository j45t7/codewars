# Highest and Lowest

### Solution:

```
function highAndLow(numbers){
  let toNumbers = numbers.split(' ')
  return `${Math.max(...toNumbers)} ${Math.min(...toNumbers)}`
}
```

```
function highAndLow(numbers){
  let toNumber =  numbers.split(' ').map(num => Number(num))
  return `${Math.max(...toNumber)} ${Math.min(...toNumber)}`
}
```