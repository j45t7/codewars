# Jaden Casing Strings

### Solution: 

```
String.prototype.toJadenCase = function () {
  return this.split(' ').map(word => `${word.charAt(0).toUpperCase()}${word.slice(1)}`).join(' ')
};
```
String.prototype.toJadenCase = function () {
  return this.split(' ').map(word => `${word.slice(0, 1).toUpperCase()}${word.slice(1)}`).join(' ')
};
```
