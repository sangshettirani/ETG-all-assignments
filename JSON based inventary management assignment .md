```python
record={11100:{'name':'rani sangshetti','pno':1234,'cgpa':8.9},
        11200:{'name':'nisha sangshetti','pno':5678,'cgpa':7.9},
        11300:{'name':'nita sangshetti','pno':9876,'cgpa':9.9}}
```


```python
record
```




    {11100: {'name': 'rani sangshetti', 'pno': 1234, 'cgpa': 8.9},
     11200: {'name': 'nisha sangshetti', 'pno': 5678, 'cgpa': 7.9},
     11300: {'name': 'nita sangshetti', 'pno': 9876, 'cgpa': 9.9}}




```python
record[11100]['name']
```




    'rani sangshetti'




```python
record[11200]
```




    {'name': 'nisha sangshetti', 'pno': 5678, 'cgpa': 7.9}




```python
reg=11100
print(record[reg]['name'])
print(record[reg]['pno'])
print(record[reg]['cgpa'])
```

    rani sangshetti
    1234
    8.9
    


```python
record[11100]['pno']
```




    1234




```python
record[11100]['pno']=456789991           #to change values
```


```python

```


```python
record
```




    {11100: {'name': 'rani sangshetti', 'pno': 456789991, 'cgpa': 8.9},
     11200: {'name': 'nisha sangshetti', 'pno': 5678, 'cgpa': 7.9},
     11300: {'name': 'nita sangshetti', 'pno': 9876, 'cgpa': 9.9}}




```python
import json
js=json.dumps(record)
#record={1001:{'name':'choko cake','qn':34,'pz':100},
#        {1002:{'name':'milk cake','qn':37,'pz':400},
#        {1003:{'name':'drink','qn':40,'pz':200}}
#fd=open("record.json",'w')
#fd.write(js)
#fd.close()
         
        
```


```python
js
```




    '{"11100": {"name": "rani sangshetti", "pno": 456789991, "cgpa": 8.9}, "11200": {"name": "nisha sangshetti", "pno": 5678, "cgpa": 7.9}, "11300": {"name": "nita sangshetti", "pno": 9876, "cgpa": 9.9}}'




```python
type(js)
```




    str




```python
record
```




    {11100: {'name': 'rani sangshetti', 'pno': 456789991, 'cgpa': 8.9},
     11200: {'name': 'nisha sangshetti', 'pno': 5678, 'cgpa': 7.9},
     11300: {'name': 'nita sangshetti', 'pno': 9876, 'cgpa': 9.9}}




```python
type(record)
```




    dict




```python
fd=open("record.json",'w')
fd.write(js)
fd.close()
 
```


```python
fd=open('record.json','r')
txt=fd.read()
fd.close()
```


```python
txt
```




    '{"11100": {"name": "rani sangshetti", "pno": 456789991, "cgpa": 8.9}, "11200": {"name": "nisha sangshetti", "pno": 5678, "cgpa": 7.9}, "11300": {"name": "nita sangshetti", "pno": 9876, "cgpa": 9.9}}'




```python
record=json.loads(txt)
```


```python
record
```




    {'11100': {'name': 'rani sangshetti', 'pno': 456789991, 'cgpa': 8.9},
     '11200': {'name': 'nisha sangshetti', 'pno': 5678, 'cgpa': 7.9},
     '11300': {'name': 'nita sangshetti', 'pno': 9876, 'cgpa': 9.9}}




```python
str(record)
```




    "{'11100': {'name': 'rani sangshetti', 'pno': 456789991, 'cgpa': 8.9}, '11200': {'name': 'nisha sangshetti', 'pno': 5678, 'cgpa': 7.9}, '11300': {'name': 'nita sangshetti', 'pno': 9876, 'cgpa': 9.9}}"




```python
import time
```


```python
time.ctime()
```




    'Fri Sep  3 23:00:55 2021'


