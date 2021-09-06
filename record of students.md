```python
fd=open('record.txt','w')
fd.write("hello world")
fd.close()
```


```python
fd=open('record.txt','a')
fd.write(" i am rani sangshetti")       #appending text to file
fd.close()
```


```python
fd=open('record.txt','a')

name=input("enter the name:")
roll_no=(input("enter the roll no:"))
marathi=(input("enter the marks in marathi:"))
english=(input("enter the marks in english:"))
hindi=(input("enter the marks in hindi:"))
data='\n'+name+","+str(roll_no)+","+str(hindi)+","+str(english)+","+str(marathi)+'\n'
fd.write(data)
fd.close()
```

    enter the name:rani
    enter the roll no:1
    enter the marks in marathi:89
    enter the marks in english:90
    enter the marks in hindi:87
    


```python
name
```




    'ranu'




```python
roll_no
```




    '1'




```python
str(roll_no)
```




    '1'




```python
data=name+","+str(roll_no)+","+str(hindi)+","+str(english)+","+str(marathi)
```


```python
data
```




    'ranu,1,96,97,98'




```python

```


```python

```
