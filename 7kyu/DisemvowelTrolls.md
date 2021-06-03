# Disemvowel Trolls

### Solution:

```
function disemvowel(str) {
  let vowels = 'aiueoAIUEO'
  return str.split('').filter(letter => !vowels.includes(letter)).join('')
}
```

```
function disemvowel(str) {
  return str.replace(/[aeiou]/ig,'')
}
```