# Correlation Matrix and Table in R
Bulding correlation matrix and transforming it into a three columns table in R.
For example:  
Supose you have the floowing matrix:
              Var1   Var2   Var3
        Var1   1      0,8    0,7
        Var2   0,8     1     0,5
        Var3   0,7    0,5     1
The code tanform this matrix into a table:

         Var1  Var1   1
         Var1  Var2   0,8
         Var1  Var3   0,7
         Var2  Var1   0,8
         Var2  Var2   1
         Var2  Var3   0,5
         Var3  Var1   0,7
         Var3  Var2   0,5
         Var3  Var3   1
