[![gordan.png](https://i.postimg.cc/R03MWK4w/gordan.png)](https://postimg.cc/NychVyy0)

# Gauss-Jordan + Regression JS library

## API

```Gordan.solveByGaussJordan(matrix)```

* ```matrix```: the augmented matrix

* **Returns:** the identity matrix with the solution coefficients

```Gordan.getLinearRegressionRect(points)```
  
* **Returns:** a list of points for the regression rect

```Gordan.getQuadraticRegressionCurve(points)```

* **Returns:** a list of points for the regression curve (cuadratic equation)

```Gordan.getRegressionPath(points, N)```

* **Returns:** a list of points for a Nth grade equation curve (```ax^N + bx^(N - 1) + cx^(N - 2) + ...```)
* ```points```: for all cases, a list of ```x, y``` points. The following formats are supported:

```json
[
  [1, 2],
  [2, 2],
  [3, 3]
]
```

```json
[
  { "x": 1, "y": 2 },
  { "x": 2, "y": 2 },
  { "x": 3, "y": 3 }
]
```

this is a work in progress!