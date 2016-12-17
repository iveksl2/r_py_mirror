In Python, you can do two-sided equalities like `3 > a > 5` and get `True` or `False`. This is a syntax error in R.

However, with the [checkr](https://github.com/peterhurford/checkr) library in R, you can do `a %within% c(3, 5)` to get the same result.
