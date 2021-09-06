```python
#list is mutable
```


```python
lst=[12,56,87]
```


```python
lst[0]=56
```


```python
lst
```




    [56, 56, 87]




```python
#to overcome this we use tuple
#tuple is imutable
```


```python
tpl=(1,6,7,8,9)
```


```python
tpl
```




    (1, 6, 7, 8, 9)




```python
tpl[0]
```




    1




```python
tpl[3]
```




    8




```python
tpl[0]=78
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-9-cff3b81d7aef> in <module>
    ----> 1 tpl[0]=78
    

    TypeError: 'tuple' object does not support item assignment



```python
#set
```


```python
lst=[1,2,5,7,6,4,8,96,3,2,8,3,2,1]
```


```python
st=set(lst)
```


```python
#removes repeated in list
```


```python
st
```




    {1, 2, 3, 4, 5, 6, 7, 8, 96}




```python
lst=list(st)
```


```python
lst
```




    [96, 1, 2, 3, 4, 5, 6, 7, 8]




```python
st[0]
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-19-028cc1d9138b> in <module>
    ----> 1 st[0]
    

    TypeError: 'set' object is not subscriptable



```python
for i in lst:
    print(i)
```

    96
    1
    2
    3
    4
    5
    6
    7
    8
    


```python
len(lst)
```




    9




```python
len(st)
```




    9




```python

```
