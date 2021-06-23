# String ends with?

### Solution:

```
function solution(str, ending){
  return ending.length === 0 ? true : str.slice(-ending.length) === ending 
}
```

```
function solution(str, ending){
  return str.endsWith(ending)
}
```