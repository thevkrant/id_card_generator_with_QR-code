<div align="center">
  <img height="60" src="https://user-images.githubusercontent.com/85709371/156916372-d8c1bbdd-5fe9-40d1-a250-5a1d4d454832.png">
</div>

<h1 align="center">Check whether the number is a Fibonacci number or not.</h1>

From the list of interview questions asked during datascience interviews. The infamous question is about checking whether the number is a Fibonacci number or not.

A Fibonacci sequence is the integer sequence of 0, 1, 1, 2, 3, 5, 8....
The first two terms are 0 and 1. All other terms are obtained by adding the preceding two terms. This means to say the nth term is the sum of (n-1)th and (n-2)th term.

* In a nutshell

"The Fibonacci sequence is a series of numbers in which each number is the sum of the two that precede it."

### Prerequisites
`Python 3`

### Source Code
```python3
def isfibo(n):
    fib_a = 0
    fib_b = 1
    while fib_a < n:
        fib_a, fib_b = fib_b, fib_a + fib_b
    if (fib_a == n):
        return("IsFibo")
    else:
        return("IsNotFibo")
```

## *Author Name*
[Vikrant](https://github.com/vikrant-v28)
