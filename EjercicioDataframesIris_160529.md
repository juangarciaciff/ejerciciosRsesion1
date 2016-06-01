# Prácticas de R y RStudio
- Ejercicio: **Data frame mtcars**
- Autor....: **Juan Antonio García Cuevas**
- Fecha....: 29/05/2016

## Con el data frame iris (viene cargado en R).

#### Muestra el data frame iris:
```
	iris
```
```
        Sepal.Length Sepal.Width Petal.Length Petal.Width    Species
    1            5.1         3.5          1.4         0.2     setosa
    2            4.9         3.0          1.4         0.2     setosa
    3            4.7         3.2          1.3         0.2     setosa
    4            4.6         3.1          1.5         0.2     setosa
    5            5.0         3.6          1.4         0.2     setosa
    6            5.4         3.9          1.7         0.4     setosa
    7            4.6         3.4          1.4         0.3     setosa
    8            5.0         3.4          1.5         0.2     setosa
    9            4.4         2.9          1.4         0.2     setosa
    10           4.9         3.1          1.5         0.1     setosa
    11           5.4         3.7          1.5         0.2     setosa
    12           4.8         3.4          1.6         0.2     setosa
    13           4.8         3.0          1.4         0.1     setosa
    14           4.3         3.0          1.1         0.1     setosa
    15           5.8         4.0          1.2         0.2     setosa
    16           5.7         4.4          1.5         0.4     setosa
    17           5.4         3.9          1.3         0.4     setosa
    18           5.1         3.5          1.4         0.3     setosa
    19           5.7         3.8          1.7         0.3     setosa
    20           5.1         3.8          1.5         0.3     setosa
    21           5.4         3.4          1.7         0.2     setosa
    22           5.1         3.7          1.5         0.4     setosa
    23           4.6         3.6          1.0         0.2     setosa
    24           5.1         3.3          1.7         0.5     setosa
    25           4.8         3.4          1.9         0.2     setosa
    26           5.0         3.0          1.6         0.2     setosa
    27           5.0         3.4          1.6         0.4     setosa
    28           5.2         3.5          1.5         0.2     setosa
    29           5.2         3.4          1.4         0.2     setosa
    30           4.7         3.2          1.6         0.2     setosa
    31           4.8         3.1          1.6         0.2     setosa
    32           5.4         3.4          1.5         0.4     setosa
    33           5.2         4.1          1.5         0.1     setosa
    34           5.5         4.2          1.4         0.2     setosa
    35           4.9         3.1          1.5         0.2     setosa
    36           5.0         3.2          1.2         0.2     setosa
    37           5.5         3.5          1.3         0.2     setosa
    38           4.9         3.6          1.4         0.1     setosa
    39           4.4         3.0          1.3         0.2     setosa
    40           5.1         3.4          1.5         0.2     setosa
    41           5.0         3.5          1.3         0.3     setosa
    42           4.5         2.3          1.3         0.3     setosa
    43           4.4         3.2          1.3         0.2     setosa
    44           5.0         3.5          1.6         0.6     setosa
    45           5.1         3.8          1.9         0.4     setosa
    46           4.8         3.0          1.4         0.3     setosa
    47           5.1         3.8          1.6         0.2     setosa
    48           4.6         3.2          1.4         0.2     setosa
    49           5.3         3.7          1.5         0.2     setosa
    50           5.0         3.3          1.4         0.2     setosa
    51           7.0         3.2          4.7         1.4 versicolor
    52           6.4         3.2          4.5         1.5 versicolor
    53           6.9         3.1          4.9         1.5 versicolor
    54           5.5         2.3          4.0         1.3 versicolor
    55           6.5         2.8          4.6         1.5 versicolor
    56           5.7         2.8          4.5         1.3 versicolor
    57           6.3         3.3          4.7         1.6 versicolor
    58           4.9         2.4          3.3         1.0 versicolor
    59           6.6         2.9          4.6         1.3 versicolor
    60           5.2         2.7          3.9         1.4 versicolor
    61           5.0         2.0          3.5         1.0 versicolor
    62           5.9         3.0          4.2         1.5 versicolor
    63           6.0         2.2          4.0         1.0 versicolor
    64           6.1         2.9          4.7         1.4 versicolor
    65           5.6         2.9          3.6         1.3 versicolor
    66           6.7         3.1          4.4         1.4 versicolor
    67           5.6         3.0          4.5         1.5 versicolor
    68           5.8         2.7          4.1         1.0 versicolor
    69           6.2         2.2          4.5         1.5 versicolor
    70           5.6         2.5          3.9         1.1 versicolor
    71           5.9         3.2          4.8         1.8 versicolor
    72           6.1         2.8          4.0         1.3 versicolor
    73           6.3         2.5          4.9         1.5 versicolor
    74           6.1         2.8          4.7         1.2 versicolor
    75           6.4         2.9          4.3         1.3 versicolor
    76           6.6         3.0          4.4         1.4 versicolor
    77           6.8         2.8          4.8         1.4 versicolor
    78           6.7         3.0          5.0         1.7 versicolor
    79           6.0         2.9          4.5         1.5 versicolor
    80           5.7         2.6          3.5         1.0 versicolor
    81           5.5         2.4          3.8         1.1 versicolor
    82           5.5         2.4          3.7         1.0 versicolor
    83           5.8         2.7          3.9         1.2 versicolor
    84           6.0         2.7          5.1         1.6 versicolor
    85           5.4         3.0          4.5         1.5 versicolor
    86           6.0         3.4          4.5         1.6 versicolor
    87           6.7         3.1          4.7         1.5 versicolor
    88           6.3         2.3          4.4         1.3 versicolor
    89           5.6         3.0          4.1         1.3 versicolor
    90           5.5         2.5          4.0         1.3 versicolor
    91           5.5         2.6          4.4         1.2 versicolor
    92           6.1         3.0          4.6         1.4 versicolor
    93           5.8         2.6          4.0         1.2 versicolor
    94           5.0         2.3          3.3         1.0 versicolor
    95           5.6         2.7          4.2         1.3 versicolor
    96           5.7         3.0          4.2         1.2 versicolor
    97           5.7         2.9          4.2         1.3 versicolor
    98           6.2         2.9          4.3         1.3 versicolor
    99           5.1         2.5          3.0         1.1 versicolor
    100          5.7         2.8          4.1         1.3 versicolor
    101          6.3         3.3          6.0         2.5  virginica
    102          5.8         2.7          5.1         1.9  virginica
    103          7.1         3.0          5.9         2.1  virginica
    104          6.3         2.9          5.6         1.8  virginica
    105          6.5         3.0          5.8         2.2  virginica
    106          7.6         3.0          6.6         2.1  virginica
    107          4.9         2.5          4.5         1.7  virginica
    108          7.3         2.9          6.3         1.8  virginica
    109          6.7         2.5          5.8         1.8  virginica
    110          7.2         3.6          6.1         2.5  virginica
    111          6.5         3.2          5.1         2.0  virginica
    112          6.4         2.7          5.3         1.9  virginica
    113          6.8         3.0          5.5         2.1  virginica
    114          5.7         2.5          5.0         2.0  virginica
    115          5.8         2.8          5.1         2.4  virginica
    116          6.4         3.2          5.3         2.3  virginica
    117          6.5         3.0          5.5         1.8  virginica
    118          7.7         3.8          6.7         2.2  virginica
    119          7.7         2.6          6.9         2.3  virginica
    120          6.0         2.2          5.0         1.5  virginica
    121          6.9         3.2          5.7         2.3  virginica
    122          5.6         2.8          4.9         2.0  virginica
    123          7.7         2.8          6.7         2.0  virginica
    124          6.3         2.7          4.9         1.8  virginica
    125          6.7         3.3          5.7         2.1  virginica
    126          7.2         3.2          6.0         1.8  virginica
    127          6.2         2.8          4.8         1.8  virginica
    128          6.1         3.0          4.9         1.8  virginica
    129          6.4         2.8          5.6         2.1  virginica
    130          7.2         3.0          5.8         1.6  virginica
    131          7.4         2.8          6.1         1.9  virginica
    132          7.9         3.8          6.4         2.0  virginica
    133          6.4         2.8          5.6         2.2  virginica
    134          6.3         2.8          5.1         1.5  virginica
    135          6.1         2.6          5.6         1.4  virginica
    136          7.7         3.0          6.1         2.3  virginica
    137          6.3         3.4          5.6         2.4  virginica
    138          6.4         3.1          5.5         1.8  virginica
    139          6.0         3.0          4.8         1.8  virginica
    140          6.9         3.1          5.4         2.1  virginica
    141          6.7         3.1          5.6         2.4  virginica
    142          6.9         3.1          5.1         2.3  virginica
    143          5.8         2.7          5.1         1.9  virginica
    144          6.8         3.2          5.9         2.3  virginica
    145          6.7         3.3          5.7         2.5  virginica
    146          6.7         3.0          5.2         2.3  virginica
    147          6.3         2.5          5.0         1.9  virginica
    148          6.5         3.0          5.2         2.0  virginica
    149          6.2         3.4          5.4         2.3  virginica
    150          5.9         3.0          5.1         1.8  virginica
```

## 1. ¿Cómo está estructurado el data frame? (utilizar las funciones str() y dim()). 

#### Muestra el número de filas, el número de columnas y los primeros valores de cada columna:
```
    str(iris)
```
```
    'data.frame':	150 obs. of  5 variables:
     $ Sepal.Length: num  5.1 4.9 4.7 4.6 5 5.4 4.6 5 4.4 4.9 ...
     $ Sepal.Width : num  3.5 3 3.2 3.1 3.6 3.9 3.4 3.4 2.9 3.1 ...
     $ Petal.Length: num  1.4 1.4 1.3 1.5 1.4 1.7 1.4 1.5 1.4 1.5 ...
     $ Petal.Width : num  0.2 0.2 0.2 0.2 0.2 0.4 0.3 0.2 0.2 0.1 ...
     $ Species     : Factor w/ 3 levels "setosa","versicolor",..: 1 1 1 1 1 1 1 1 1 1 ...
```

#### Muestra el número de filas y columnas:
```
    dim(iris)
```
```
    [1] 150   5
```

## 2. ¿De qué tipo es cada una de las variables del data frame?.
```
    mode(iris[[1]])
    mode(iris[[2]])
    mode(iris[[3]])
    mode(iris[[4]])
    mode(iris[[5]])
```
```
    [1] "numeric"
    [1] "numeric"
    [1] "numeric"
    [1] "numeric"
    [1] "numeric"
```

## 3. Utilizar la función summary() para obtener un resumen de los estadísticos de las variables. 

#### Muestra el resumen de valores estadísticos de cada columna (menor, primer cuarto, mediana, media, tercer cuarto y mayor):
```
    summary(iris)
```
```
      Sepal.Length    Sepal.Width     Petal.Length    Petal.Width          Species  
     Min.   :4.300   Min.   :2.000   Min.   :1.000   Min.   :0.100   setosa    :50  
     1st Qu.:5.100   1st Qu.:2.800   1st Qu.:1.600   1st Qu.:0.300   versicolor:50  
     Median :5.800   Median :3.000   Median :4.350   Median :1.300   virginica :50  
     Mean   :5.843   Mean   :3.057   Mean   :3.758   Mean   :1.199                  
     3rd Qu.:6.400   3rd Qu.:3.300   3rd Qu.:5.100   3rd Qu.:1.800                  
     Max.   :7.900   Max.   :4.400   Max.   :6.900   Max.   :2.500                  
```

## 4. Comprobar con las funciones mean(), range(), que se obtienen los mismos valores. 

#### Muestra la media de las columnas numéricas:
```
    apply(iris[,1:4], 2, mean)
```
```
    Sepal.Length  Sepal.Width Petal.Length  Petal.Width 
        5.843333     3.057333     3.758000     1.199333 
```

# Muestra los rangos (min, max) de todas las columnas:
```
    apply(iris[,1:5], 2, range)
```
```
         Sepal.Length Sepal.Width Petal.Length Petal.Width Species    
    [1,] "4.3"        "2.0"       "1.0"        "0.1"       "setosa"   
    [2,] "7.9"        "4.4"       "6.9"        "2.5"       "virginica"
```

## 5. Cambia los valores de las variables Sepal.Length Sepal.Width de las 5 primeras observaciones por NA. 

#### Muestra todas las filas de las dos columnas solicitadas, antes de ser modificadas:
```
    iris[, c("Sepal.Length", "Sepal.Width")]
```
```
        Sepal.Length Sepal.Width
    1            5.1         3.5
    2            4.9         3.0
    3            4.7         3.2
    4            4.6         3.1
    5            5.0         3.6
    6            5.4         3.9
    7            4.6         3.4
    8            5.0         3.4
    9            4.4         2.9
    10           4.9         3.1
    11           5.4         3.7
    12           4.8         3.4
    13           4.8         3.0
    14           4.3         3.0
    15           5.8         4.0
    16           5.7         4.4
    17           5.4         3.9
    18           5.1         3.5
    19           5.7         3.8
    20           5.1         3.8
    21           5.4         3.4
    22           5.1         3.7
    23           4.6         3.6
    24           5.1         3.3
    25           4.8         3.4
    26           5.0         3.0
    27           5.0         3.4
    28           5.2         3.5
    29           5.2         3.4
    30           4.7         3.2
    31           4.8         3.1
    32           5.4         3.4
    33           5.2         4.1
    34           5.5         4.2
    35           4.9         3.1
    36           5.0         3.2
    37           5.5         3.5
    38           4.9         3.6
    39           4.4         3.0
    40           5.1         3.4
    41           5.0         3.5
    42           4.5         2.3
    43           4.4         3.2
    44           5.0         3.5
    45           5.1         3.8
    46           4.8         3.0
    47           5.1         3.8
    48           4.6         3.2
    49           5.3         3.7
    50           5.0         3.3
    51           7.0         3.2
    52           6.4         3.2
    53           6.9         3.1
    54           5.5         2.3
    55           6.5         2.8
    56           5.7         2.8
    57           6.3         3.3
    58           4.9         2.4
    59           6.6         2.9
    60           5.2         2.7
    61           5.0         2.0
    62           5.9         3.0
    63           6.0         2.2
    64           6.1         2.9
    65           5.6         2.9
    66           6.7         3.1
    67           5.6         3.0
    68           5.8         2.7
    69           6.2         2.2
    70           5.6         2.5
    71           5.9         3.2
    72           6.1         2.8
    73           6.3         2.5
    74           6.1         2.8
    75           6.4         2.9
    76           6.6         3.0
    77           6.8         2.8
    78           6.7         3.0
    79           6.0         2.9
    80           5.7         2.6
    81           5.5         2.4
    82           5.5         2.4
    83           5.8         2.7
    84           6.0         2.7
    85           5.4         3.0
    86           6.0         3.4
    87           6.7         3.1
    88           6.3         2.3
    89           5.6         3.0
    90           5.5         2.5
    91           5.5         2.6
    92           6.1         3.0
    93           5.8         2.6
    94           5.0         2.3
    95           5.6         2.7
    96           5.7         3.0
    97           5.7         2.9
    98           6.2         2.9
    99           5.1         2.5
    100          5.7         2.8
    101          6.3         3.3
    102          5.8         2.7
    103          7.1         3.0
    104          6.3         2.9
    105          6.5         3.0
    106          7.6         3.0
    107          4.9         2.5
    108          7.3         2.9
    109          6.7         2.5
    110          7.2         3.6
    111          6.5         3.2
    112          6.4         2.7
    113          6.8         3.0
    114          5.7         2.5
    115          5.8         2.8
    116          6.4         3.2
    117          6.5         3.0
    118          7.7         3.8
    119          7.7         2.6
    120          6.0         2.2
    121          6.9         3.2
    122          5.6         2.8
    123          7.7         2.8
    124          6.3         2.7
    125          6.7         3.3
    126          7.2         3.2
    127          6.2         2.8
    128          6.1         3.0
    129          6.4         2.8
    130          7.2         3.0
    131          7.4         2.8
    132          7.9         3.8
    133          6.4         2.8
    134          6.3         2.8
    135          6.1         2.6
    136          7.7         3.0
    137          6.3         3.4
    138          6.4         3.1
    139          6.0         3.0
    140          6.9         3.1
    141          6.7         3.1
    142          6.9         3.1
    143          5.8         2.7
    144          6.8         3.2
    145          6.7         3.3
    146          6.7         3.0
    147          6.3         2.5
    148          6.5         3.0
    149          6.2         3.4
    150          5.9         3.0
```

#### Muestra las 5 primeras filas de las dos columnas solicitadas, antes de ser modificadas:
```
    iris[1:5, c("Sepal.Length", "Sepal.Width")]
```
```
      Sepal.Length Sepal.Width
    1          5.1         3.5
    2          4.9         3.0
    3          4.7         3.2
    4          4.6         3.1
    5          5.0         3.6
```

#### Asigna NA a las 5 primeras filas de las dos columnas solicitadas:
```
    iris[1:5, c("Sepal.Length", "Sepal.Width")] <- NA
```

#### Muestra las 5 primeras filas de las dos columnas solicitadas, después de ser modificadas:
```
    iris[1:5, c("Sepal.Length", "Sepal.Width")]
```
```
      Sepal.Length Sepal.Width
    1           NA          NA
    2           NA          NA
    3           NA          NA
    4           NA          NA
    5           NA          NA
```

#### Muestra todas las filas de las dos columnas solicitadas, después de ser modificadas:
```
    iris[, c("Sepal.Length", "Sepal.Width")]
```
```
        Sepal.Length Sepal.Width
    1             NA          NA
    2             NA          NA
    3             NA          NA
    4             NA          NA
    5             NA          NA
    6            5.4         3.9
    7            4.6         3.4
    8            5.0         3.4
    9            4.4         2.9
    10           4.9         3.1
    11           5.4         3.7
    12           4.8         3.4
    13           4.8         3.0
    14           4.3         3.0
    15           5.8         4.0
    16           5.7         4.4
    17           5.4         3.9
    18           5.1         3.5
    19           5.7         3.8
    20           5.1         3.8
    21           5.4         3.4
    22           5.1         3.7
    23           4.6         3.6
    24           5.1         3.3
    25           4.8         3.4
    26           5.0         3.0
    27           5.0         3.4
    28           5.2         3.5
    29           5.2         3.4
    30           4.7         3.2
    31           4.8         3.1
    32           5.4         3.4
    33           5.2         4.1
    34           5.5         4.2
    35           4.9         3.1
    36           5.0         3.2
    37           5.5         3.5
    38           4.9         3.6
    39           4.4         3.0
    40           5.1         3.4
    41           5.0         3.5
    42           4.5         2.3
    43           4.4         3.2
    44           5.0         3.5
    45           5.1         3.8
    46           4.8         3.0
    47           5.1         3.8
    48           4.6         3.2
    49           5.3         3.7
    50           5.0         3.3
    51           7.0         3.2
    52           6.4         3.2
    53           6.9         3.1
    54           5.5         2.3
    55           6.5         2.8
    56           5.7         2.8
    57           6.3         3.3
    58           4.9         2.4
    59           6.6         2.9
    60           5.2         2.7
    61           5.0         2.0
    62           5.9         3.0
    63           6.0         2.2
    64           6.1         2.9
    65           5.6         2.9
    66           6.7         3.1
    67           5.6         3.0
    68           5.8         2.7
    69           6.2         2.2
    70           5.6         2.5
    71           5.9         3.2
    72           6.1         2.8
    73           6.3         2.5
    74           6.1         2.8
    75           6.4         2.9
    76           6.6         3.0
    77           6.8         2.8
    78           6.7         3.0
    79           6.0         2.9
    80           5.7         2.6
    81           5.5         2.4
    82           5.5         2.4
    83           5.8         2.7
    84           6.0         2.7
    85           5.4         3.0
    86           6.0         3.4
    87           6.7         3.1
    88           6.3         2.3
    89           5.6         3.0
    90           5.5         2.5
    91           5.5         2.6
    92           6.1         3.0
    93           5.8         2.6
    94           5.0         2.3
    95           5.6         2.7
    96           5.7         3.0
    97           5.7         2.9
    98           6.2         2.9
    99           5.1         2.5
    100          5.7         2.8
    101          6.3         3.3
    102          5.8         2.7
    103          7.1         3.0
    104          6.3         2.9
    105          6.5         3.0
    106          7.6         3.0
    107          4.9         2.5
    108          7.3         2.9
    109          6.7         2.5
    110          7.2         3.6
    111          6.5         3.2
    112          6.4         2.7
    113          6.8         3.0
    114          5.7         2.5
    115          5.8         2.8
    116          6.4         3.2
    117          6.5         3.0
    118          7.7         3.8
    119          7.7         2.6
    120          6.0         2.2
    121          6.9         3.2
    122          5.6         2.8
    123          7.7         2.8
    124          6.3         2.7
    125          6.7         3.3
    126          7.2         3.2
    127          6.2         2.8
    128          6.1         3.0
    129          6.4         2.8
    130          7.2         3.0
    131          7.4         2.8
    132          7.9         3.8
    133          6.4         2.8
    134          6.3         2.8
    135          6.1         2.6
    136          7.7         3.0
    137          6.3         3.4
    138          6.4         3.1
    139          6.0         3.0
    140          6.9         3.1
    141          6.7         3.1
    142          6.9         3.1
    143          5.8         2.7
    144          6.8         3.2
    145          6.7         3.3
    146          6.7         3.0
    147          6.3         2.5
    148          6.5         3.0
    149          6.2         3.4
    150          5.9         3.0
```

## 6. ¿Qué pasa si usamos ahora las funciones mean(), range() con las variables Sepal.Length y Sepal.Width? ¿Tiene el mismo problema la función summary()?

#### Las funciones mean y range dan un resultado NA, porque están teniendo en cuenta los valores NA:
```
    mean(iris[["Sepal.Length"]])
    range(iris[["Sepal.Length"]])
```
```
    [1] NA
    [1] NA NA
```
```
    mean(iris[["Sepal.Width"]])
    range(iris[["Sepal.Width"]])
```
```
    [1] NA
    [1] NA NA
```

#### La función summary no presenta ningún problema:
```
    summary(iris[["Sepal.Length"]])
```
```
       Min. 1st Qu.  Median    Mean 3rd Qu.    Max.    NA's 
      4.300   5.200   5.800   5.877   6.400   7.900       5 
```
```
    summary(iris[["Sepal.Width"]])
```
```
       Min. 1st Qu.  Median    Mean 3rd Qu.    Max.    NA's 
       2.00    2.80    3.00    3.05    3.30    4.40       5 
```

## 7. Ver la documentación de mean(), range(), etc. ¿Qué parámetro habría que cambiar para arreglar el problema anterior?. 

#### Consultar la documentación:
```
    ?mean
    ?range
```

#### Con el parámetro "na.rm=TRUE" las funciones mean y range dan el resultado esperado, porque no están teniendo en cuenta los valores NA:
```
    mean(iris[["Sepal.Length"]], na.rm=TRUE)
    mean(iris[["Sepal.Width"]], na.rm=TRUE)
    range(iris[["Sepal.Length"]], na.rm=TRUE)
    range(iris[["Sepal.Width"]], na.rm=TRUE)
```
```
    [1] 5.877241
    [1] 3.049655
    [1] 4.3 7.9
    [1] 2.0 4.4
```

## 8. Visto lo anterior, ¿por qué es importante codificar los missing values como NA y no como 0, por ejemplo? 

Porque si se codificaran con 0 se tendrían en cuenta en el cálculo de la media, por lo que el valor obtenido sería inferior al correcto.

## 9. Eliminar los valores NA usando na.omit(). 
```
    na.omit(iris)
```
```
        Sepal.Length Sepal.Width Petal.Length Petal.Width    Species
    6            5.4         3.9          1.7         0.4     setosa
    7            4.6         3.4          1.4         0.3     setosa
    8            5.0         3.4          1.5         0.2     setosa
    9            4.4         2.9          1.4         0.2     setosa
    10           4.9         3.1          1.5         0.1     setosa
    11           5.4         3.7          1.5         0.2     setosa
    12           4.8         3.4          1.6         0.2     setosa
    13           4.8         3.0          1.4         0.1     setosa
    14           4.3         3.0          1.1         0.1     setosa
    15           5.8         4.0          1.2         0.2     setosa
    16           5.7         4.4          1.5         0.4     setosa
    17           5.4         3.9          1.3         0.4     setosa
    18           5.1         3.5          1.4         0.3     setosa
    19           5.7         3.8          1.7         0.3     setosa
    20           5.1         3.8          1.5         0.3     setosa
    21           5.4         3.4          1.7         0.2     setosa
    22           5.1         3.7          1.5         0.4     setosa
    23           4.6         3.6          1.0         0.2     setosa
    24           5.1         3.3          1.7         0.5     setosa
    25           4.8         3.4          1.9         0.2     setosa
    26           5.0         3.0          1.6         0.2     setosa
    27           5.0         3.4          1.6         0.4     setosa
    28           5.2         3.5          1.5         0.2     setosa
    29           5.2         3.4          1.4         0.2     setosa
    30           4.7         3.2          1.6         0.2     setosa
    31           4.8         3.1          1.6         0.2     setosa
    32           5.4         3.4          1.5         0.4     setosa
    33           5.2         4.1          1.5         0.1     setosa
    34           5.5         4.2          1.4         0.2     setosa
    35           4.9         3.1          1.5         0.2     setosa
    36           5.0         3.2          1.2         0.2     setosa
    37           5.5         3.5          1.3         0.2     setosa
    38           4.9         3.6          1.4         0.1     setosa
    39           4.4         3.0          1.3         0.2     setosa
    40           5.1         3.4          1.5         0.2     setosa
    41           5.0         3.5          1.3         0.3     setosa
    42           4.5         2.3          1.3         0.3     setosa
    43           4.4         3.2          1.3         0.2     setosa
    44           5.0         3.5          1.6         0.6     setosa
    45           5.1         3.8          1.9         0.4     setosa
    46           4.8         3.0          1.4         0.3     setosa
    47           5.1         3.8          1.6         0.2     setosa
    48           4.6         3.2          1.4         0.2     setosa
    49           5.3         3.7          1.5         0.2     setosa
    50           5.0         3.3          1.4         0.2     setosa
    51           7.0         3.2          4.7         1.4 versicolor
    52           6.4         3.2          4.5         1.5 versicolor
    53           6.9         3.1          4.9         1.5 versicolor
    54           5.5         2.3          4.0         1.3 versicolor
    55           6.5         2.8          4.6         1.5 versicolor
    56           5.7         2.8          4.5         1.3 versicolor
    57           6.3         3.3          4.7         1.6 versicolor
    58           4.9         2.4          3.3         1.0 versicolor
    59           6.6         2.9          4.6         1.3 versicolor
    60           5.2         2.7          3.9         1.4 versicolor
    61           5.0         2.0          3.5         1.0 versicolor
    62           5.9         3.0          4.2         1.5 versicolor
    63           6.0         2.2          4.0         1.0 versicolor
    64           6.1         2.9          4.7         1.4 versicolor
    65           5.6         2.9          3.6         1.3 versicolor
    66           6.7         3.1          4.4         1.4 versicolor
    67           5.6         3.0          4.5         1.5 versicolor
    68           5.8         2.7          4.1         1.0 versicolor
    69           6.2         2.2          4.5         1.5 versicolor
    70           5.6         2.5          3.9         1.1 versicolor
    71           5.9         3.2          4.8         1.8 versicolor
    72           6.1         2.8          4.0         1.3 versicolor
    73           6.3         2.5          4.9         1.5 versicolor
    74           6.1         2.8          4.7         1.2 versicolor
    75           6.4         2.9          4.3         1.3 versicolor
    76           6.6         3.0          4.4         1.4 versicolor
    77           6.8         2.8          4.8         1.4 versicolor
    78           6.7         3.0          5.0         1.7 versicolor
    79           6.0         2.9          4.5         1.5 versicolor
    80           5.7         2.6          3.5         1.0 versicolor
    81           5.5         2.4          3.8         1.1 versicolor
    82           5.5         2.4          3.7         1.0 versicolor
    83           5.8         2.7          3.9         1.2 versicolor
    84           6.0         2.7          5.1         1.6 versicolor
    85           5.4         3.0          4.5         1.5 versicolor
    86           6.0         3.4          4.5         1.6 versicolor
    87           6.7         3.1          4.7         1.5 versicolor
    88           6.3         2.3          4.4         1.3 versicolor
    89           5.6         3.0          4.1         1.3 versicolor
    90           5.5         2.5          4.0         1.3 versicolor
    91           5.5         2.6          4.4         1.2 versicolor
    92           6.1         3.0          4.6         1.4 versicolor
    93           5.8         2.6          4.0         1.2 versicolor
    94           5.0         2.3          3.3         1.0 versicolor
    95           5.6         2.7          4.2         1.3 versicolor
    96           5.7         3.0          4.2         1.2 versicolor
    97           5.7         2.9          4.2         1.3 versicolor
    98           6.2         2.9          4.3         1.3 versicolor
    99           5.1         2.5          3.0         1.1 versicolor
    100          5.7         2.8          4.1         1.3 versicolor
    101          6.3         3.3          6.0         2.5  virginica
    102          5.8         2.7          5.1         1.9  virginica
    103          7.1         3.0          5.9         2.1  virginica
    104          6.3         2.9          5.6         1.8  virginica
    105          6.5         3.0          5.8         2.2  virginica
    106          7.6         3.0          6.6         2.1  virginica
    107          4.9         2.5          4.5         1.7  virginica
    108          7.3         2.9          6.3         1.8  virginica
    109          6.7         2.5          5.8         1.8  virginica
    110          7.2         3.6          6.1         2.5  virginica
    111          6.5         3.2          5.1         2.0  virginica
    112          6.4         2.7          5.3         1.9  virginica
    113          6.8         3.0          5.5         2.1  virginica
    114          5.7         2.5          5.0         2.0  virginica
    115          5.8         2.8          5.1         2.4  virginica
    116          6.4         3.2          5.3         2.3  virginica
    117          6.5         3.0          5.5         1.8  virginica
    118          7.7         3.8          6.7         2.2  virginica
    119          7.7         2.6          6.9         2.3  virginica
    120          6.0         2.2          5.0         1.5  virginica
    121          6.9         3.2          5.7         2.3  virginica
    122          5.6         2.8          4.9         2.0  virginica
    123          7.7         2.8          6.7         2.0  virginica
    124          6.3         2.7          4.9         1.8  virginica
    125          6.7         3.3          5.7         2.1  virginica
    126          7.2         3.2          6.0         1.8  virginica
    127          6.2         2.8          4.8         1.8  virginica
    128          6.1         3.0          4.9         1.8  virginica
    129          6.4         2.8          5.6         2.1  virginica
    130          7.2         3.0          5.8         1.6  virginica
    131          7.4         2.8          6.1         1.9  virginica
    132          7.9         3.8          6.4         2.0  virginica
    133          6.4         2.8          5.6         2.2  virginica
    134          6.3         2.8          5.1         1.5  virginica
    135          6.1         2.6          5.6         1.4  virginica
    136          7.7         3.0          6.1         2.3  virginica
    137          6.3         3.4          5.6         2.4  virginica
    138          6.4         3.1          5.5         1.8  virginica
    139          6.0         3.0          4.8         1.8  virginica
    140          6.9         3.1          5.4         2.1  virginica
    141          6.7         3.1          5.6         2.4  virginica
    142          6.9         3.1          5.1         2.3  virginica
    143          5.8         2.7          5.1         1.9  virginica
    144          6.8         3.2          5.9         2.3  virginica
    145          6.7         3.3          5.7         2.5  virginica
    146          6.7         3.0          5.2         2.3  virginica
    147          6.3         2.5          5.0         1.9  virginica
    148          6.5         3.0          5.2         2.0  virginica
    149          6.2         3.4          5.4         2.3  virginica
    150          5.9         3.0          5.1         1.8  virginica
```

## 10. Calcular la media de la variable Petal.Length para cada uno de las distintas especies (Species). Pista: usar la función tapply().

#### Vector de valores:
```
    PetalLength <- iris[["Petal.Length"]]
    PetalLength
```
```
      [1] 1.4 1.4 1.3 1.5 1.4 1.7 1.4 1.5 1.4 1.5 1.5 1.6 1.4 1.1 1.2 1.5 1.3 1.4 1.7 1.5 1.7 1.5 1.0 1.7 1.9 1.6 1.6 1.5 1.4 1.6 1.6 1.5 1.5 1.4 1.5 1.2 1.3 1.4 1.3 1.5 1.3 1.3
     [43] 1.3 1.6 1.9 1.4 1.6 1.4 1.5 1.4 4.7 4.5 4.9 4.0 4.6 4.5 4.7 3.3 4.6 3.9 3.5 4.2 4.0 4.7 3.6 4.4 4.5 4.1 4.5 3.9 4.8 4.0 4.9 4.7 4.3 4.4 4.8 5.0 4.5 3.5 3.8 3.7 3.9 5.1
     [85] 4.5 4.5 4.7 4.4 4.1 4.0 4.4 4.6 4.0 3.3 4.2 4.2 4.2 4.3 3.0 4.1 6.0 5.1 5.9 5.6 5.8 6.6 4.5 6.3 5.8 6.1 5.1 5.3 5.5 5.0 5.1 5.3 5.5 6.7 6.9 5.0 5.7 4.9 6.7 4.9 5.7 6.0
    [127] 4.8 4.9 5.6 5.8 6.1 6.4 5.6 5.1 5.6 6.1 5.6 5.5 4.8 5.4 5.6 5.1 5.1 5.9 5.7 5.2 5.0 5.2 5.4 5.1
```

#### Vector de especie de cada uno de los valores:
```
    Species <- iris[["Species"]]
    Species
```
```
      [1] setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa    
     [16] setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa    
     [31] setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa    
     [46] setosa     setosa     setosa     setosa     setosa     versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor
     [61] versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor
     [76] versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor
     [91] versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor virginica  virginica  virginica  virginica  virginica 
    [106] virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica 
    [121] virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica 
    [136] virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica 
    Levels: setosa versicolor virginica
```

#### Factor:
```
    FactorSpecies <- factor(Species)
    FactorSpecies
```
```
      [1] setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa    
     [16] setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa    
     [31] setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa     setosa    
     [46] setosa     setosa     setosa     setosa     setosa     versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor
     [61] versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor
     [76] versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor
     [91] versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor versicolor virginica  virginica  virginica  virginica  virginica 
    [106] virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica 
    [121] virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica 
    [136] virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica  virginica 
    Levels: setosa versicolor virginica
```

#### Niveles:
```
    LevelsSpecies <- levels(FactorSpecies)
    LevelsSpecies
```
```
    [1] "setosa"     "versicolor" "virginica" 
```

#### Media por especie:
```
    PetalLengthMedia <- tapply(PetalLength, FactorSpecies, mean)
    PetalLengthMedia
```
```
        setosa versicolor  virginica 
         1.462      4.260      5.552 
```
