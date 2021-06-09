# Is this a triangle?

### Solution:

```
function isTriangle(a,b,c)
{
   return a + b > c && a + c > b && b + c > a
}
```

```
function isTriangle(a,b,c)
{
   return a + b <= c || a + c <= b || b + c <= a  ? false :true 
}
```