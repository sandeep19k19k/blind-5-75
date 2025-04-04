# blind-5-75
Maximum subarray
Maximum Subarray.

key things : 

first element is the max sub array in the beginning.

As we iterate , add elements one by one .

check if this is maximum.

if sum of subarray is negative, better we dicard the sum, so that we start afresh with next element ,irrespective of whether it is negative or positive.

Time complexity: O(n)

Space complexity: O(1)



I actually tried to use prefix sum array method ,which has O(n) space complexity ,but comitted few logical errors and was only able to cross 200 test cases(misssed around 10). 

Tried to keep a check on beginning and ending of subarray .

But kadane algo looks much optimal,simple and better without any doubt.

Key takeway: If sub array sum turns negative. discard it. I mean make the variable equal to zero.
