# Euler Project 1: Multiples of 3 and 5

# If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.
# 
# Find the sum of all the multiples of 3 or 5 below 1000.

divided_by_3_or_5 <- function(value) {
  if (value %% 3 == 0 || value %% 5 == 0) {
    return(T)
  } else {
    return(F)
  }
}

vektor <- 1:10000

# Timing execution

## start clock
ptm <- proc.time()

sum(Filter(f = divided_by_3_or_5, x = vektor))

# Stop clock
proc.time() - ptm
unname(ptm[1])
