```python
a=[[1,2,3,4,5],         #2- dimentional list
   [3,4,6,78]]
```


```python
type(a)
```




    list




```python
 b=[1,2,3,4,5]            #1-dimentional list
```


```python
type(b)
```




    list




```python
 a=[[1,2,3,4,5],         #2- dimentional list
   [3,4,6,7,8],
   [5,6,9,2,6],
   [3,7,6,4,2]]   
```


```python
a[0]
```




    [1, 2, 3, 4, 5]




```python
a[2]
```




    [5, 6, 9, 2, 6]




```python
len(a)
```




    4




```python
a[0][1]
```




    2




```python
a[2][2]
```




    9




```python
a[1][3]
```




    7




```python
a[1:]
```




    [[3, 4, 6, 7, 8], [5, 6, 9, 2, 6], [3, 7, 6, 4, 2]]




```python
a[1:2]
```




    [[3, 4, 6, 7, 8]]




```python
a[1:3]
```




    [[3, 4, 6, 7, 8], [5, 6, 9, 2, 6]]




```python
#      name  r_no math eng
info=[['rani',1,98,80,78],
     ['nisha',2,54,78,79],
     ['rutuja',3,67,89,70],]
```


```python
info
```




    [['rani', 1, 98, 80, 78], ['nisha', 2, 54, 78, 79], ['rutuja', 3, 67, 89, 70]]




```python
info[0]
```




    ['rani', 1, 98, 80, 78]




```python
info[1][0]
```




    'nisha'




```python
score=[]
roll_no=int(input('enter roll no:'))
for i in info:
    if(roll_no==i[1]):
        print('name:',i[0])
        print('maths',i[2])
        print('english:',i[3])
        print('hindi:',i[4])
        per=((i[2]+i[3]+i[4])/300)*100
        print('percentage:',per)
        if(per>=75):
            grade='A'
        elif(per<75  and per>=60):
            grade='B'
        elif(per<60  and per>=35):
            grade='C'
        elif(per<35):
            grade='fail'
        score.append([i[1],i[0],per,grade])  
score
```

    enter roll no:1
    name: rani
    maths 98
    english: 80
    hindi: 78
    percentage: 85.33333333333334
    




    [[1, 'rani', 85.33333333333334, 'A']]




```python

```


```python

```
