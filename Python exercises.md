# Startup

1. Don't forget to fetch your class notes repo AND the textbook repo. 
2. Copy these files from the textbook repo into your class notes/exercises folder:
    -  `ledatascifi-2022/handouts/Python exercises.ipynb`
    - `ledatascifi-2022/content/01/06_python.ipynb`
3. Suggested: Open this exercise file on one side of your Jupyterlab screen and the two files above on the other side of your screen. 


## As you solve the questions below:
- use comments to take notes about code you're writing as you figure things out
- take big picture notes in the module 1 notes file


## Python essentials

Loosely covers the [python essentials in 1.7.2](https://ledatascifi.github.io/ledatascifi-2022/content/01/06_python.html#python-essentials)


```python
# this is guided discussion AND practice,
# follow along!

# start running code from the textbook here
# add as many new code cells as you want 
```

## Exercises (try, pair, share)

1. Say hi to the person next to you
1. [Try to guess each other's lie](https://github.com/orgs/LeDataSciFi/teams/classmates-2022/discussions/3)


```python
L=[8, 5, 6, 3, 7]
```

Write code that does the following with  the vector `L`. Discuss with the person next to you as needed:

1. Returns the length.
1. Returns the largest element.
1. Returns the smallest element.
1. Returns the total of the vector.
2. Returns the first element. See [this awesome answer](https://stackoverflow.com/questions/509211/understanding-slice-notation?rq=1) to learn about "slicing" lists in Python. If that link is dead: https://stackoverflow.com/questions/509211/understanding-slice-notation?rq=1 
2. Returns the last element.
2. Returns the first 2 elements.
2. Returns the last 2 elements.
2. Returns the odd numbered elements (i.e. [8,6,7].
1. Clear your output and restart the kernel, then rerun your code. 



```python
L=[8, 5, 6, 3, 7]
#1
len(L)
min(L)
max(L)
sum(L)
L[0::2]
L[-1]

```




    7




```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python

```


```python
#Week 2 class 1
```


```python
len(L)

```




    5




```python
max(L)
```




    8




```python
min(L)
```




    3




```python
sum(L)
```




    29




```python
L[0] # t oaccces list elements , use sq brackets, 0 is the index, for the first one
```




    8




```python
L[len(L)-1] can acces from the end
```




    7




```python
L[-1]  counting from the the last
```




    7




```python
L[
```


```python

```


```python

```


```python

```


```python
# class 4 week 2
```


```python

```


```python
# get the price
# add the cost of port
```


```python

```


```python
stonks = ['GM','F','TSLA','MSFT']
prices = {'GM':10,'F':20,'TSLA':1000,'MSFT':500}
shares = {'GM':4,'F':3,'TSLA':2,'MSFT':2}
weights = {'GM':0.35,'F':0.4,'TSLA':0.3,'MSFT':-0.05} # not typo
industry = {'GM':'auto','F':'auto','TSLA':'auto','MSFT':'tech'}



```


```python
total=0
for stonk in stonks:
    price=prices[stonk]
    num_shares=shares[stonk]
    total=price*num_shares+total
    print(stonk, total)
```

    GM 40
    F 100
    TSLA 2100
    MSFT 3100
    


```python
# if statemet

for stonk in stonks:
    if(industry[stonk] == 'auto'):
        print(industry)
        
total=0
for stonk in stonks:
    if(industry[stonk] == 'auto'):
        price=prices[stonk]
        num_shares=shares[stonk]
        total=price*num_shares+total
        print(stonk, total)
```

    {'GM': 'auto', 'F': 'auto', 'TSLA': 'auto', 'MSFT': 'tech'}
    {'GM': 'auto', 'F': 'auto', 'TSLA': 'auto', 'MSFT': 'tech'}
    {'GM': 'auto', 'F': 'auto', 'TSLA': 'auto', 'MSFT': 'tech'}
    GM 40
    F 100
    TSLA 2100
    


```python

```


```python

```


```python

```


```python

```
