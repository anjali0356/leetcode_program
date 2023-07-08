# Minimum number of jumps
## Medium
<div class="problems_problem_content__Xm_eO" style="user-select: text;"><p style="user-select: text;"><span style="font-size: 18px; user-select: text;">Given an array of <strong style="user-select: text;">N</strong> integers <strong style="user-select: text;">arr[]</strong> where each element represents the <strong style="user-select: text;">maximum</strong> length of the jump that can be made forward from that element. This means if arr[i] = x, then we can jump any distance y such that y&nbsp;≤ x.<br style="user-select: text;">
Find&nbsp;the minimum number of jumps to reach the end of the array (starting from the first element).&nbsp;If an element is <strong style="user-select: text;">0</strong>, then you cannot move through that element.</span><br style="user-select: text;">
<br style="user-select: text;">
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Note: </strong>Return -1 if you can't reach the end of the array.</span></p>

<p style="user-select: text;"><br style="user-select: text;">
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Example 1:</strong></span><span style="font-size: 18px; user-select: text;"> </span></p>

<pre style="user-select: text;"><span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Input:</strong></span>
<span style="font-size: 18px; user-select: text;">N = 11 </span>
<span style="font-size: 18px; user-select: text;">arr[] = {1, 3, 5, 8, 9, 2, 6, 7, 6, 8, 9} </span>
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Output:</strong> 3 </span>
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Explanation:</strong> </span>
<span style="font-size: 18px; user-select: text;">First jump from 1st element to 2nd 
element with value 3. Now, from here 
we jump to 5th element with value 9, 
and from here we will jump to the last. </span></pre>

<p style="user-select: text;"><strong style="user-select: text;"><span style="font-size: 18px; user-select: text;">Example 2:</span></strong></p>

<pre style="user-select: text;"><strong style="user-select: text;"><span style="font-size: 18px; user-select: text;">Input :</span></strong>
<span style="font-size: 18px; user-select: text;">N = 6
arr = {1, 4, 3, 2, 6, 7}</span>
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Output:</strong> 2 
<strong style="user-select: text;">Explanation: 
</strong>First we jump from the 1st to 2nd element 
and then jump to the last element.</span>
</pre>

<p style="user-select: text;"><br style="user-select: text;">
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Your task:</strong><br style="user-select: text;">
You don't need to read input or print anything. Your task is to complete function <strong style="user-select: text;">minJumps()</strong> which takes the array <strong style="user-select: text;">arr</strong> and it's size <strong style="user-select: text;">N</strong> as input parameters and returns the minimum number of jumps. If not possible return -1.</span></p>

<p style="user-select: text;"><br style="user-select: text;">
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Expected Time Complexity:&nbsp;</strong>O(N)<br style="user-select: text;">
<strong style="user-select: text;">Expected Space Complexity:&nbsp;</strong>O(1)</span></p>

<p style="user-select: text;"><br style="user-select: text;">
<span style="font-size: 18px; user-select: text;"><strong style="user-select: text;">Constraints:</strong><br style="user-select: text;">
1 ≤ N ≤ 10<sup style="user-select: text;">7</sup><br style="user-select: text;">
0 ≤ arr<sub style="user-select: text;">i</sub> ≤ 10<sup style="user-select: text;">7</sup></span></p>
</div>