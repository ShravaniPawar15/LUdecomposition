
# LU_DECOMPOSITION

LU decomposition of a matrix is the factorization of a given square matrix into two triangular matrices, one upper triangular matrix and one lower triangular matrix, such that the product of these two matrices gives the original matrix.

The LU decomposition of a matrix 
A
 is the pair of matrices 
L
 and 
U
 such that:

1. A=LU
2. L is a lower-triangular matrix with all diagonal entries equal to 1
3. U is an upper-triangular matrix


## Algorithm

Let AX=B be the systems of equations and A = [aij], b = (b1, b2, …, bn), x = (x1, x2, …, xn)

**1** Read the matrix A = [aij], i,j = 1, 2, ….n and the right hand vector b = (b1, b2, …, bn)

**2** Calculate the lower triangular matrix and upper triangular matrix.

**3** Print L and U matrix.

**4** Find Y by solving LY=B by forward substitution.

**5** Find X by solving UX=Y by forward substitution.

**6** Print X as output.




## Run Program

[This will be written at the start of the program]
  
```bash
  %%writefile filename.c
```

For compailation:

```bash
  %%shell
```

```bash
  gcc filename.c -o outputfilename
```

Run program:
```bash
  ./outputfilename
```

