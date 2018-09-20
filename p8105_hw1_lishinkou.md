p8105\_hw1\_lishinkou
================
Shane

Problem 1
---------

``` r
p1_df = tibble(
  vec_numeric = runif(10, 0, 5),
  vec_logical = vec_numeric > 2,
  vec_char = letters[1:10],
  vec_factor = factor(rep(c('fac1', 'fac2'), 5))
)
mean(p1_df$vec_numeric)
```

    ## [1] 3.059678

``` r
mean(p1_df$vec_logical)
```

    ## [1] 0.8

``` r
mean(p1_df$vec_char)
```

    ## Warning in mean.default(p1_df$vec_char): argument is not numeric or
    ## logical: returning NA

    ## [1] NA

``` r
mean(p1_df$vec_factor)
```

    ## Warning in mean.default(p1_df$vec_factor): argument is not numeric or
    ## logical: returning NA

    ## [1] NA
