Ans1)

```python
cricket = [('Sachin Tendulkar', 34357), ('Ricky Ponting', 27483), ('Jack Kallis', 25534), ('Virat Kohli', 24936)] 
cricket.sort(key=lambda a: a[1])
print(cricket)
```

    [('Virat Kohli', 24936), ('Jack Kallis', 25534), ('Ricky Ponting', 27483), ('Sachin Tendulkar', 34357)]

Ans2)

```python
a = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 
list(map(lambda x : x**2 , a ))
```




    [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]


Ans3)

```python
l = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10] 
list(map(lambda x : str(x),l))

```




    ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10']


Ans4)

```python
from functools import  reduce

```


```python
b = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25]
reduce(lambda x,y : x*y,b)
```




    15511210043330985984000000


Ans5)

```python
c = [2, 3, 6, 9, 27, 60, 90, 120, 55, 46] 
list(filter(lambda x : x%2==0 and x%3==0,c))
```




    [6, 60, 90, 120]


Ans6)


```python
s = ['python', 'php', 'aba', 'radar', 'level'] 
palindrome = list(filter(lambda x : (x=="".join(reversed(x))),s))
```


```python
palindrome
```




    ['php', 'aba', 'radar', 'level']




```python

```

