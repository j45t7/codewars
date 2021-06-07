# Complementary DNA

### Solution:

```
function DNAStrand(dna){
let pairs = {'A': 'T', 'T':'A', 'C': 'G', 'G':'C'}
  return dna.split('').map(letter => pairs[letter]).join('')
}
```
```
function DNAStrand(dna){ 
  return dna.split('').map(letter=>  letter === 'A' ? letter.replace('A', 'T') : letter === 'T' ? letter.replace('T', 'A') : letter === 'C' ? letter.replace('C', 'G')
    : letter === 'G'? letter.replace('G', 'C')
    : null ).join('')
}
```