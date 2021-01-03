CODE SIGNAL

adjacentElementsProduct

```python
def adjacentElementsProduct(inputArray):
    tmp = []
    for i in range(len(inputArray)-1):
        tmp.append(inputArray[i]*inputArray[i+1])
    return max(tmp)
```

아래의 방법은 반복문을 comprehensive하게 표현한 방법이다.

```python
def adjacentElementsProduct(inputArray):
    return max([inputArray[i] * inputArray[i+1] for i in range(len(inputArray)-1)])
```

    

