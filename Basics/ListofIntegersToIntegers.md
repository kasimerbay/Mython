```Python
#convert list of integers to integer
def convert(list):

    s = [str(i) for i in list]
    res = int("".join(s))
      
    return(res)
```