# Growth of a Population

### Solution: 

```
function nbYear(p0, percent, aug, p) {
   for ( i = 0; p0 < p; i++) {
    p0 += ((p0 * (percent / 100)) + aug);
  }
  return i
}
```

