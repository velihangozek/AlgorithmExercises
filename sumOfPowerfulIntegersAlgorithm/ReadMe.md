Given two positive integers x and y in string type, an integer is powerful if it is equal to x^i + y^j for some integers i >= 0 and j >= 0.

Return a list of all powerful integers that have value less than or equal to bound.

You may return the answer in ascending order.  In your answer, each value should occur at most once.

Example 1:
Input: 2 3 10
//Input Order(x y bound)
Output: 2,3,4,5,7,9,10
Explanation: 
2 = 2^0 + 3^0
3 = 2^1 + 3^0
4 = 2^0 + 3^1
5 = 2^1 + 3^1
7 = 2^2 + 3^1
9 = 2^3 + 3^0
10 = 2^0 + 3^2

Example 2:
Input: 3 5 15
//Input Order(x y bound)
Output: 2,4,6,8,10,14

Note:
1 <= x <= 100
1 <= y <= 100
0 <= bound <= 10^6

How your application code will be tested?
- Test data (and more different data) will be populated to your application by automated test. You can enter and test your test data from Input text field. You do not need to manually populate test data in the code. But you need to parse application arguments in your code assuming that each data will be separated by space.
- Output should just print resulting data as expected in Output section of Example test scenario defined above. Application should terminate after printing Output. No need to print out any more data such as log or debug information in your final code.
- You can write all the code in main() or write separate methods and call methods in main(); it depends on your design criteria. First you should ensure that your code works correctly for Input and Output.
