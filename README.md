# Bidirectional Dictionary 

Python 3.6 Implementation of 2.7 bidirectional dictionary solution found [here](https://stackoverflow.com/questions/3318625/efficient-bidirectional-hash-table-in-python)

use example: 
```
my_dict = Bidict({'a':'x', 'b':'y', 'c':'x'})

print(my_dict)
# {'a': 'x', 'b': 'y', 'c': 'x'}
print(my_dict['a'])
# x
print(my_dict.inverse['x'])
# ['a', 'c']
```
