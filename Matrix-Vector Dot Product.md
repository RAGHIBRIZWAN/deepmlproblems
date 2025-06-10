```py
def matrix_dot_vector(a: list[list[int|float]], b: list[int|float]) -> list[int|float]:
	c = []
	adding = 0

	length1 = len(a)
	length2 = len(b)

	if length1 == length2:
		for i in range(length1):
			adding = 0
			for j in range(length2):
				adding += a[i][j] * b[j]
			c.append(adding)
		return c
	else:
		return -1
	pass
```
