# Categorize New Member

### Solution:

```
function openOrSenior(data){
  let returned = []
  for (let i = 0; i < data.length; i++){
    data[i][0] >= 55 && data[i][1] > 7 ? returned.push('Senior') : returned.push('Open')
  }
  return returned
}
```

```
function openOrSenior(data){
  return data.map(([age, handicap]) => age >= 55 && handicap > 7 ? 'Senior': 'Open')
}

```