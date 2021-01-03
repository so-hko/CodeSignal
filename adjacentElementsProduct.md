CODE SIGNAL

adjacentElementsProduct

```python
def adjacentElementsProduct(inputArray):
    tmp = []
    for i in range(len(inputArray)-1):
        tmp.append(inputArray[i]*inputArray[i+1])
    return max(tmp)```
    
```python
def adjacentElementsProduct(inputArray):
    return max([inputArray[i] * inputArray[i+1] for i in range(len(inputArray)-1)])
    
위의 방법이 더 좋은 방법인 것 같다.
