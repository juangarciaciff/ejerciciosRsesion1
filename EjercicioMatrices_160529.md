# Prácticas de R y RStudio
- Ejercicio: **Matrices**
- Autor....: **Juan Antonio García Cuevas**
- Fecha....: 29/05/2016

#### Crear la matriz 4×5:
```
    a <- matrix(1:20, nrow=4, ncol=5, byrow = TRUE)
    a
         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    2    3    4    5
    [2,]    6    7    8    9   10
    [3,]   11   12   13   14   15
    [4,]   16   17   18   19   20
```

### Extraer los elementos A[4,3], A[3,4], A[2,5]:
```
    a[4,3]
    [1] 18
    a[3,4]
    [1] 14
    a[2,5]
    [1] 10
```

#### Reemplazar dichos elementos con 0:
```
    a[4,3] <- 0
    a[2,5] <- 0
    a[3,4] <- 0
    a
         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    2    3    4    5
    [2,]    6    7    8    9    0
    [3,]   11   12   13    0   15
    [4,]   16   17    0   19   20
```

#### Crear la matriz identidad 5×5v
```
    ?diag
    i <- diag(,5,5)
    i
         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    0    0    0    0
    [2,]    0    1    0    0    0
    [3,]    0    0    1    0    0
    [4,]    0    0    0    1    0
    [5,]    0    0    0    0    1
```

#### Convertir la matriz A anterior en una matriz cuadrada B agregando al final una fila de unos:
```
    ?rbind
    b <- rbind(a, 1)
    b
         [,1] [,2] [,3] [,4] [,5]
    [1,]    1    2    3    4    5
    [2,]    6    7    8    9    0
    [3,]   11   12   13    0   15
    [4,]   16   17    0   19   20
    [5,]    1    1    1    1    1
```

#### Calcular la inversa de la matriz B con la funcion solve():
```
    bi <- solve(b)
    bi
                [,1] [,2]        [,3]          [,4]       [,5]
    [1,] -0.50158730 -0.3 -0.14285714 -5.555556e-02  5.7619048
    [2,]  0.27460317  0.4  0.21428571  1.111111e-01 -6.8095238
    [3,]  0.05555556  0.0  0.00000000 -5.555556e-02  0.8333333
    [4,]  0.07142857  0.0 -0.07142857 -9.912706e-18  0.7142857
    [5,]  0.10000000 -0.1  0.00000000 -6.938894e-18  0.5000000
```

#### Multiplicar B por su inversa:
```
    bm <- b %*% bi
    bm
                 [,1]          [,2]         [,3]         [,4]          [,5]
    [1,] 1.000000e+00  0.000000e+00 0.000000e+00 8.921435e-18 -1.332268e-15
    [2,] 2.220446e-16  1.000000e+00 1.110223e-16 1.328303e-16 -4.440892e-15
    [3,] 4.440892e-16  0.000000e+00 1.000000e+00 2.289835e-16 -5.329071e-15
    [4,] 2.220446e-16  0.000000e+00 2.220446e-16 1.000000e+00 -8.881784e-15
    [5,] 2.775558e-17 -2.775558e-17 0.000000e+00 3.965082e-18  1.000000e+00
```

#### Comprobar si el resultado es exactamente la matriz identidad I:
```
    bm == i
          [,1]  [,2]  [,3]  [,4]  [,5]
    [1,]  TRUE  TRUE  TRUE FALSE FALSE
    [2,] FALSE  TRUE FALSE FALSE FALSE
    [3,] FALSE  TRUE FALSE FALSE FALSE
    [4,] FALSE  TRUE FALSE  TRUE FALSE
    [5,] FALSE FALSE  TRUE FALSE FALSE

    bm - i
                 [,1]          [,2]          [,3]         [,4]          [,5]
    [1,] 0.000000e+00  0.000000e+00  0.000000e+00 8.921435e-18 -1.332268e-15
    [2,] 2.220446e-16  0.000000e+00  1.110223e-16 1.328303e-16 -4.440892e-15
    [3,] 4.440892e-16  0.000000e+00 -2.220446e-16 2.289835e-16 -5.329071e-15
    [4,] 2.220446e-16  0.000000e+00  2.220446e-16 0.000000e+00 -8.881784e-15
    [5,] 2.775558e-17 -2.775558e-17  0.000000e+00 3.965082e-18 -3.330669e-16
```

#### En caso contrario, calcular el rerror o precisión de la operación:
```
    p <- sum(abs(bm - i)) / length(b)
    p
    [1] 8.876233e-16
```
