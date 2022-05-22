# mergesort
merge
# Merge Sort

[16,21,11,8,12,22] -> Merge Sort 

### 1. Write the stages of the above array according to the sort type.

##### Firstly, it is started to divide the array into two, then the division is done in such a way that each element remains single.

|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|-----------------------------------------------  |- |- |- |- |- |- |- |- |- |- |- |- |
|Dividing the array into two sub-arrays           |  |  |  |16|21|11|8 |12|22|  |  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|Dividing the sub-arrays among themselves.        |  |  |16|21|11|  |  |8 |12|22|  |  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                 |  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                 |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                 |16|  |21|  |11|  |  |8 |  |12|  |22|

##### After the division process is completed, single-element arrays are combined in binary form until a sequential array is created.

|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|----------------------------------------------- |- |- |- |- |- |- |- |- |- |- |- |- |
|                                                |16|  |21|  |11|  |  |8 |  |12|  |22|
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                |  |16|21|  |11|  |  |8 |  |12|22|  |
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                |  |  |11|16|21|  |  |8 |12|22|  |  |
|                                                |  |  |  |  |  |  |  |  |  |  |  |  |
|                                                |  |  |  |8 |11|12|16|21|22|  |  |  |


### 2. Big-O Notation

O(n*(logn)) --> O(6*(log6))
