```py
matrix = [[1, 2], [3, 4]]
scalar = 2
result = []

for i in range(len(matrix)):
    final = []
    for j in range(len(matrix[0])):
        final.append(matrix[i][j] * scalar)
    result.append(final)
    
print(result)
```
