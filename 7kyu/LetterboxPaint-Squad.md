# Letterbox Paint-Squad

### Solution:

```
var paintLetterboxes = function(start, end) {
  let counter = Array(10).fill(0)
  let allNumbers = []
  for(let i = start; i<= end; i++){
     let allNumbers = i.toString().split('')
     for(let j =0; j<allNumbers.length; j++){
        counter[allNumbers[j]]++
     }
  } 
  return counter
}
```

```
var paintLetterboxes = function(start, end) {
 return Array(1 + end - start).fill().map((_,i) => i+ start).flatMap(num => num.toString().split('')).reduce((tally, number) => (tally[number] += 1, tally), Array(10).fill(0))
}

```