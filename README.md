L2_EX1 – filter, map, reduce in Kotlin

screenshot:
<img width="944" height="425" alt="image" src="https://github.com/user-attachments/assets/64a724c6-75d8-4816-b1b8-4c83993fe37f" />


This program:
- Creates a list of integers from 1 to 100.
- Uses filter { it % 2 == 0 } to get all even numbers.
- Uses map { it * it } to get the square of each number.
- Uses reduce { acc, n -> acc + n } to get the sum of all numbers.

