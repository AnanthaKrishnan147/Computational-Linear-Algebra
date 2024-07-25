## Psuedocode for Linear Algebra

```python
FUNCTION matrix(a,b)
$A=\begin{pmatrix}
1&2&3\\
3&4&5\\
5&6&7
\end{pmatrix}$

FUNCTION matrix_sum(a,b):
  Get the number of rows and columns of a and b
  FOR i in row(a):
    FOR i in col(b):
      C[i][j]=a[i][j]+b[i][j]
  RETURN c
END FUNCTION

FUNCTION solution (A,b):
  create augmented matrix:K=[A|b]
Reduce to roe echolon form
```
