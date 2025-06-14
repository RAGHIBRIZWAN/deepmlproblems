```py
matrix = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
mode = 'column'
num = 0
div = 0
total = 0
final = []
if  mode == 'column':
    for j in range(len(matrix[0])):
        num = 0
        div = 0
        total = 0
        for i in range(len(matrix)):
            num += matrix[i][j]
            div += 1
        total = num/div
        final.append(total)
        
if  mode == 'row':
    for i in range(len(matrix)):
        num = 0
        div = 0
        total = 0
        for j in range(len(matrix[0])):
            num += matrix[i][j]
            div += 1
        total = num/div
        final.append(total)
        
print(final)
```
