# MATLAB-Cheatsheet
## MATLAB Terminal Commands
**clear** - Clears all the variables  
**clc** - Clear the screen

## Matrix Creation
| Matrix Type | Size | Syntax | Result |
| :--- | :---: | :--- | :---: |
| Scalar | 1 * 1 | x = 4 <br/> y = 10 | 4 <br/> 10 |
| 1-by-2 Row Vector | 1 * 2 | x = [3 5] | 3 &nbsp; &nbsp; 5 |
| 1-by-3 Row Vector | 1 * 3 | x = [10 20 30] | 10 &nbsp; &nbsp; 20 &nbsp; &nbsp; 30 |
| 2-by-1 Column Vector | 2 * 1 | x = [10;20] | 10 <br/> 20 |
| 3-by-1 Column Vector | 3 * 1 | x = [10;20;30] | 10 <br/> 20 <br/> 30 |
| 2-by-2 Matrix | 2 * 2 | x = [10 20;30 40] | 10 &nbsp; &nbsp; 20 <br/> 30 &nbsp; &nbsp; 40 |
| 3-by-3 Matrix | 3 * 3 | x = [10 20 30;40 50 60] | 10 &nbsp; &nbsp; 20 &nbsp; &nbsp; 30 <br/> 40 &nbsp; &nbsp; 50 &nbsp; &nbsp; 60 |

## Matrix Creation - Some shorthand
### Create a row vector with 1 to 10
```
Syntax - x = 1:10
Result - 1   2   3   4   5   6   7   8   9   10
```
### Create a row vector with 1 to 10 with 2 spacing
```
Syntax - x = 2:2:10
Result - 2   4   6   8   10
```
### Create a row vector from 2 to 10 with 5 elements
```
Syntax - x = linspace(2, 10, 5)
Result - 2   4   6   8   10
```
### Convert a row vector into a column vector
```
Syntax - y = x'
Result - 2
         4
         6
         8
         10
```
### Create a column vector from 5 to 9 with 2 spacing
```
Syntax - x = (5:2:9)'
Result - 2
         4
         6
         8
         10
```