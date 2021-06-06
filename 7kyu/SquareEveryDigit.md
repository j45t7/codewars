# Square Every Digit

### Solution:

```
function squareDigits(num){
  //may the code be with you
  return +num.toString().split('').map(num=> num**2).join('')
}
```
```
function squareDigits(num){
  //may the code be with you
  let number = num.toString().split('').map(num => num**2).join('')
  return Number(number)
}
```