# Create Phone Number

### Solution:

```
function createPhoneNumber(numbers){
  return `(${numbers.slice(0,3).join('')}) ${numbers.slice(3,6).join('')}-${numbers.slice(6,10).join('')}`
}
```

```
function createPhoneNumber(numbers){
  return numbers.reduce((a, b) => a.replace('x', b), '(xxx) xxx-xxxx')
}
```
