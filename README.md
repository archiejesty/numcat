# Numcat
A Package to concatenate floating point numbers under a set of rules.

## Installation
Run `pip install numcat` in your command prompt.

## Usage
```python
from numcat import functions
```

## Rules & Defintion
Concatenation is the action of appending two or more objects usually strings or integers end-to-end.

1. The fractional and integer parts are concatenated seperately to one another
   1.1 concatenate 1.2 equals 11.12 

print(functions.concat(1.1,2.2))
```