# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm (i)
1. Input the Matrix: Accept a square matrix from the user.
2. Decompose the Matrix: Use the lu() function to perform LU decomposition.
3. Extract L and U: Obtain the lower (L) and upper (U) triangular matrices.
4. Display the Results: Print the L and U matrices.
## Algorithm (ii)
1. Input the Matrix: The code takes the input matrix and the constant vector
   b from the user, converts them into NumPy arrays
2. LU Decomposition: The lu_factor function from scipy.linalg performs LU decomposition on the
   input matrix, decomposing it into lower triangular (L) and upper triangular (U) matrices
3. Solving th linear sytem of Equations
4. Output Solution: The calculated solution vector solution is printed to the console.

## Program:
(i) To find the L and U matrix
```

    Program to find the L and U matrix.
    Developed by: B.Surya Prakash
    RegisterNumber: 24900718
    import numpy as np
    from scipy.linalg import lu 
    matrix=np.array(eval(input()))
    piv,l_matrix,u_matrix=lu(matrix)
    print(l_matrix)
    print(u_matrix)

```
(ii) To find the LU Decomposition of a matrix
```

    Program to find the LU Decomposition of a matrix.
    Developed by:B.Surya Prakash 
    RegisterNumber: 24900718
    import numpy as np
    from scipy.linalg import lu_factor,lu_solve
    matrix=np.array(eval(input()))
    b=np.array(eval(input()))
    x=lu_factor(matrix)
    solution=lu_solve(x,b)
    print(solution)

```


## Output:
![lu decomposition]()
![alt text](Exp-5(1).png)
![alt text](Exp-5(2).png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

