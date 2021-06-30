# Who likes it?

### Solution:

```
function likes(names) {
  return names.length >= 4 ? `${names[0]}, ${names[1]} and ${names.length -2} others like this`
  : names.length === 3 ? `${names[0]}, ${names[1]} and ${names[2]} like this`
  : names.length === 2 ? `${names[0]} and ${names[1]} like this`
  : names.length === 1 ? `${names[0]} likes this`
  : `no one likes this`
}
```