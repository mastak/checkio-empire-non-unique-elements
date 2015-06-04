**Optional Goals**

**Rank 2**:
 
An array can contains latin letters. Letters are counted as case insensitive,
so "a" == "A", so in ["d", "D", "A"] only one unique element - "A".

_Precondition Rank 2_

```
all(len(str(x)) == 1 and str(x).isalnum() for x in array)
```
