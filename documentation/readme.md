To provide the user human readable documenation on a functions purpose & mapping of input to output.
Within both interpretors a function can be proceeded with a `?` to retrieve the documentation. I.E. `?sum`  
Lets replicate a very simple base `sum` function:

*R*: 
Within R to provide the user this human readable information one traditionally uses the Roxygen2 library.
```r
#' Return the sum of 2 integers 
#' @param x1 numeric. The first number 
#' @param x2 numeric. The second number 
add_two_nums <- function(x1, x2) {
  x1 + x2
}
```

*Python*: 
Within Python one achieves function documentation through a docstring 
```python
def add_two_nums(x1, x2):
    """Return the sum of 2 integers; int, int -> int""" 
    return x1 + x2
```

Both Roxygen & Docstrings provide more extensive functionality then this simple example. 
  See [here](https://github.com/klutometis/roxygen) for additional details on Roxygen. 
  See [here](https://www.python.org/dev/peps/pep-0257/) for additional details on Docstrings. 




