[![gordan.png](https://i.postimg.cc/R03MWK4w/gordan.png)](https://postimg.cc/NychVyy0)

## Gauss-Jordan + Regression JS library

## API

```Gordan.getLinearRegressionRect(points)```

Returns a list of points for the regression rect

```Gordan.getQuadraticRegressionCurve(points)```

Returns a list of points for the regression curve (cuadratic equation)

```Gordan.getRegressionPath(points, 6)```

Returns a list of points for a curve with a 6th grade equation  (ax^6 + bx^5 + cx^4 +...)

points can be:

```json
[
  [1, 2],
  [2, 2],
  [3, 3]
]
```

or:


```json
[
  { x: 1, y: 2 },
  { x: 2, y: 2 },
  { x: 3, y: 3 }
]
```

this is a work in progress!