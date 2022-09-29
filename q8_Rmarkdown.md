q8_Rmarkdown
================
2022-09-29

## Section 1.1

Do some fancy programming, for example, uh, for loop?

``` r
a <- c(1,2,3)
result <- c()
for (i in a) {
  result <- c(i**10)
}
print(result)
```

    ## [1] 59049

It seems that we did this in a wrong way without adding the new value
after the old onw it.

## Section 1.2

Let’s try to correct it.

``` r
a <- c(1,2,3)
result <- c()
for (i in a) {
  result <- append(result, i**10)
}
print(result)
```

    ## [1]     1  1024 59049

We did it!
