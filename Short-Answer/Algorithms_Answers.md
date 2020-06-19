#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)

O(n). It runs once for each value in n since even though the while is `a < n * n * n` a is `a = a + n * n` so the first two ns get canceled out.

b)

O(n log n). The number if iterations increases each faster than n increases but it increases slower than O(n^2)

c)

O(n). The recursion happens once for every bunny given.

## Exercise II

Start of by dropping egg on the middle floor.
If it breaks go to floor below to see if it breaks, if it breaks return above floor else set ceiling to current floor.
Else set base to current floor.
Repeat until found.
O(log n)