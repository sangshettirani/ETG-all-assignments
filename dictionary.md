# dictionary in python


```python
#dict is key value pair
dct={"name":'ashish','english':89,'marathi':97
    
}
```


```python
dct
```




    {'name': 'ashish', 'english': 89, 'marathi': 97}




```python
dct[0]
```


    ---------------------------------------------------------------------------

    KeyError                                  Traceback (most recent call last)

    <ipython-input-3-bddb1a64b6de> in <module>
    ----> 1 dct[0]
    

    KeyError: 0



```python
#using key we can access values but by using index we cant access
dct['name']
```




    'ashish'




```python
dct['english']
```




    89




```python
len(dct)
```




    3




```python
# to access keys in the dict we use keys() fun syntax:dict_name.keys()
dct.keys()
```


```python
# to access values in the dict we use values() fun syntax:dict_name.values()
dct.values()
```




    dict_values(['ashish', 89, 97])



# multiple list (


```python
data={100:{'name':'rani','roll_no':1,'div':'A'},
      101:{'name':'nisha','roll_no':2,'div':'B'},
      102:{'name':'rutuja','roll_no':3,'div':'C'}}
```


```python
data
```




    {100: {'name': 'rani', 'roll_no': 1, 'div': 'A'},
     101: {'name': 'nisha', 'roll_no': 2, 'div': 'B'},
     102: {'name': 'rutuja', 'roll_no': 3, 'div': 'C'}}




```python
data[101]
```




    {'name': 'nisha', 'roll_no': 2, 'div': 'B'}




```python
data[100]
```




    {'name': 'rani', 'roll_no': 1, 'div': 'A'}




```python
data[102]
```




    {'name': 'rutuja', 'roll_no': 3, 'div': 'C'}




```python
data[100]['name']
```




    'rani'




```python
data[100]['div']
```




    'A'




```python
data[100]['name']='manisha'
```


```python
data
```




    {100: {'name': 'manisha', 'roll_no': 1, 'div': 'A'},
     101: {'name': 'nisha', 'roll_no': 2, 'div': 'B'},
     102: {'name': 'rutuja', 'roll_no': 3, 'div': 'C'}}




```python
del data[100]
```


```python
data
```




    {101: {'name': 'nisha', 'roll_no': 2, 'div': 'B'},
     102: {'name': 'rutuja', 'roll_no': 3, 'div': 'C'}}




```python

```
