# Bitwise-Operators
Bitwise operators are extremely useful. Unfortunately, they often go overlooked - this repository is here to change that.

Bitwise operators are similar to logical operators but they work on a smaller scale. What is special about bitwise operators is that they compare corresponding bits of the number. Although bitwise operators work at the binary level they are used as operators between regular floating point numbers and integers. 

For example, we would call:
* ```5 <bitwise-operator> 2``` not ```0101 <bitwise-operator> 0010``` 

## Types of Bitwise Operators
There are six btiwise operators in python:
* Bitwise AND - ```&```
* Bitwise OR - ```|```
* Bitwise XOR - ```^```
* Bitwise NOT - ```~```
* Bitwsie right shift - ```>>```
* Bitwise left shift - ```<<```

#### Bitwise AND (```&```)
Bitwise AND returns 1 if both bits are 1 ```else``` 0.

| First Bit (A) | Second Bit (B) |  ```A & B```  |
|      :---:    |      :---:     |     :---:   |
|        1      |        1       |       1     |
|        1      |        0       |       0     |
|        0      |        1       |       0     |
|        0      |        0       |       0     |

For example, 

```A = 5``` (0101 in binary) 

```B = 6``` (0110 in binary)

then ```A & B = 0100``` which is equivalent to ```A & B = 4```

#### Bitwise OR (```|```)
Bitwise OR returns 1 if either bit is 1 ```else``` 0.

| First Bit (A) | Second Bit (B) |  ```A | B```  |
|      :---:    |      :---:     |     :---:   |
|        1      |        1       |       1     |
|        1      |        0       |       1     |
|        0      |        1       |       1     |
|        0      |        0       |       0     |

For example, 

```A = 5``` (0101 in binary) 

```B = 6``` (0110 in binary)

then ```A | B = 0111``` which is equivalent to ```A & B = 7```


#### Bitwise XOR (```^```)
Bitwise XOR returns 1 if one of the bits is 1 and the other is 0 ```else``` 0.

| First Bit (A) | Second Bit (B) |  ```A ^ B```  |
|      :---:    |      :---:     |     :---:   |
|        1      |        1       |       0     |
|        1      |        0       |       1     |
|        0      |        1       |       1     |
|        0      |        0       |       0     |

For example, 

```A = 5``` (0101 in binary) 

```B = 6``` (0110 in binary)

then ```A & B = 0011``` which is equivalent to ```A & B = 3```
