# Subarray with given sum
## Easy
<div class="problems_problem_content__Xm_eO" style="user-select: text;"><p style="user-select: text;"><span style="font-size: 18px; user-select: text;">Given an unsorted array <strong style="user-select: text;">A </strong>of size <strong style="user-select: text;">N</strong>&nbsp;that contains only&nbsp;positive integers, find a continuous sub-array that adds to a given number <strong style="user-select: text;">S&nbsp;</strong>and return the left and right index(<strong style="user-select: text;">1-based indexing</strong>) of that subarray.</span></p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;">In case of multiple subarrays, return the subarray indexes which come first on moving from left to right.</span></p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Note</strong>:-&nbsp;You have to return an ArrayList consisting of two elements left and right. In case no such subarray exists return an array consisting of element <strong style="user-select: text;">-1</strong>.</span></p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Example 1:</strong></span></p>

<pre style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Input:
</strong>N = 5, S = 12
A[] = {1,2,3,7,5}
<strong style="user-select: text;">Output: </strong>2 4<strong style="user-select: text;">
Explanation: </strong>The sum of elements 
from 2nd position to 4th position 
is 12.</span></pre>

<p style="user-select: text;">&nbsp;</p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Example 2:</strong></span></p>

<pre style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Input:
</strong>N = 10, S = 15
A[] = {1,2,3,4,5,6,7,8,9,10}
<strong style="user-select: text;">Output: </strong>1 5<strong style="user-select: text;">
Explanation: </strong>The sum of elements 
from 1st position to 5th position
is 15.</span>
</pre>

<p style="user-select: text;">&nbsp;</p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Your Task:</strong><br style="user-select: text;">
You don't need to read input or print anything. The task is to complete the function <strong style="user-select: text;">subarraySum</strong>() which takes arr, N, and S as input parameters and returns an <strong style="user-select: text;">ArrayList&nbsp;</strong>containing the&nbsp;<strong style="user-select: text;">starting </strong>and <strong style="user-select: text;">ending </strong>positions&nbsp;of the&nbsp;first such occurring subarray from the left where sum equals to S. The <strong style="user-select: text;">two indexes in the array</strong> should be according to <strong style="user-select: text;">1-based indexing</strong>. If no such subarray is found, return an array consisting of only one element that is -1.</span></p>

<p style="user-select: text;">&nbsp;</p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Expected Time Complexity:&nbsp;</strong>O(N)<br style="user-select: text;">
<strong style="user-select: text;">Expected Auxiliary Space:&nbsp;</strong>O(1)</span></p>

<p style="user-select: text;">&nbsp;</p>

<p style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Constraints:</strong><br style="user-select: text;">
1 &lt;= N &lt;= 10<sup style="user-select: text;">5</sup></span><br style="user-select: text;">
<span style="font-size: 18px; user-select: text;">1 &lt;= A</span><sub style="user-select: text;">i</sub><span style="font-size: 18px; user-select: text;"> &lt;= 10<sup style="user-select: text;">9</sup></span><br style="user-select: text;">
<span style="font-size: 18px; user-select: text;">0&lt;= S</span><span style="font-size: 18px; user-select: text;">&nbsp;&lt;= 10<sup style="user-select: text;">14</sup></span></p>
</div>