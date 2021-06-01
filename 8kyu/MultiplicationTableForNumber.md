# Multiplication table for number

### Solution:

```
function multiTable(number) {
  let table = []
  for (let i = 1; i <= 10; i++){
    table.push(`${i} * ${number} = ${i * number}`)
  }
  return table.join('\n')
}
```
```
function multiTable(number) {
return [1,2,3,4,5,6,7,8,9,10].map(item => `${item} * ${number} = ${item*number}`).join('\n');
}
```