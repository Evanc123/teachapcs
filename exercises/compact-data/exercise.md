1. Write a program that reads a text file (`compact.txt`) and stores the <word data-key="int">integers</word> in an <word data-key="array">array</word>. 
2. Write a <word data-key="function">function</word> `compact` that eliminates all 0's (zeroes) from its array parameter, leaving the relative order of the other elements unchanged. All local variables within this function must be scalar; in other words, you may not use a second array to solve the problem. You must use the <word data-key="function-header">function header</word> `public static int compact (int list[], int N)`
3. Your method's <word data-key="precondition">precondition</word> is: list contains integers; N is the number of integers in the array (N <= list.length)
4. Your method's <word data-key="postcondition">postcondition</word> is: all non-zero elements in the array are at the front of the array
5. Your method should <word data-key="_return">return</word>: the number of non-zero elements – all of which are at the beginning of the array, N has been updated
6. Do not solve the problem by printing out only the non-zero values in the array. Instead, `compact` must move all non-zero elements to the front of the array.
