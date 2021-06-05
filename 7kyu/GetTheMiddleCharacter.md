# Get the Middle Character

### Solution:

```
function getMiddle(s)
{
  return s.substring(Math.round(s.length/2)-1, s.length/2+1)
}
```

```
function getMiddle(s)
{
   return s.length % 2 === 0 ? s.slice(s.length/2-1, s.length/2+1) : s.slice(s.length/2, s.length/2+1)
}
```
