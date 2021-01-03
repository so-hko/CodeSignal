CODE SIGNAL

adjacentElementsProduct

```python
def adjacentElementsProduct(inputArray):
    tmp = []
    for i in range(len(inputArray)-1):
        tmp.append(inputArray[i]*inputArray[i+1])
    return max(tmp)```
