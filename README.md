L2_EX1 – filter, map, reduce in Kotlin

This program:
- Creates a list of integers from 1 to 100.
- Uses filter { it % 2 == 0 } to get all even numbers.
- Uses map { it * it } to get the square of each number.
- Uses reduce { acc, n -> acc + n } to get the sum of all numbers.
