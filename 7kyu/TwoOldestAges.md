# Two Oldest Ages

### Solution:

```
function twoOldestAges(ages){
  return ages.sort((a,b) => a -b).slice(-2)
}
```

```
function twoOldestAges(ages){
  let oldest = 0
  let second = 0
  for (i = 0; i < ages.length; i++){
    if(ages[i] > oldest){
      second = oldest
      oldest = ages[i]
    } else if(ages[i] > second){
      second = ages[i]
    }
  }
  return [second, oldest]
}
```