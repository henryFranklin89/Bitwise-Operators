# Bitwise-Operators
Bitwise operators are extremely useful. Unfortunately, they often go overlooked - this repository is here to change that.

Bitwise operators are similar to logical operators but they work on a smaller scale. What is special about bitwise operators is that they compare corresponding bits of the number. Although bitwise operators work at the binary level they are used as operators between regular floating point numbers and integers. 

For example, we would call:
* ```5 <bitwise-operator> 2``` not ```0011 <bitwise-operator> 0001``` 

## Types of Bitwise Operators
There are six btiwise operators in python:
* Bitwise AND - ```&```
* Bitwise OR - ```|```
* Bitwise NOT - ```~```
* Bitwise XOR - ```^```
* Bitwsie right shift - ```>>```
* Bitwise left shift - ```<<```

#### Bitwise AND (```&```)
Bitwise AND returns 1 if both bits are 1 ```else``` 0.

| First Bit  | Second Bit |  &-Return  |
|    :---:   |    :---:   |    :---:   |
|      1     |      1     |      1     |
|      1     |      0     |      0     |
|      0     |      1     |      0     |
|      0     |      0     |      0     |
