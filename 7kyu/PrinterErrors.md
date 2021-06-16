# Printer Errors

### Solution:

```
function printerError(s) {
   return `${s.replace(/[a-m]/gi, '').length}/${s.length}`
}
```