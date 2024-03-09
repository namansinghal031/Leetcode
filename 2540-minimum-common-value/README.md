<h2><a href="https://leetcode.com/problems/minimum-common-value/">2540. Minimum Common Value</a></h2><h3>Easy</h3><hr><div style="user-select: auto;"><p style="user-select: auto;">Given two integer arrays <code style="user-select: auto;">nums1</code> and <code style="user-select: auto;">nums2</code>, sorted in non-decreasing order, return <em style="user-select: auto;">the <strong style="user-select: auto;">minimum integer common</strong> to both arrays</em>. If there is no common integer amongst <code style="user-select: auto;">nums1</code> and <code style="user-select: auto;">nums2</code>, return <code style="user-select: auto;">-1</code>.</p>

<p style="user-select: auto;">Note that an integer is said to be <strong style="user-select: auto;">common</strong> to <code style="user-select: auto;">nums1</code> and <code style="user-select: auto;">nums2</code> if both arrays have <strong style="user-select: auto;">at least one</strong> occurrence of that integer.</p>

<p style="user-select: auto;">&nbsp;</p>
<p style="user-select: auto;"><strong class="example" style="user-select: auto;">Example 1:</strong></p>

<pre style="user-select: auto;"><strong style="user-select: auto;">Input:</strong> nums1 = [1,2,3], nums2 = [2,4]
<strong style="user-select: auto;">Output:</strong> 2
<strong style="user-select: auto;">Explanation:</strong> The smallest element common to both arrays is 2, so we return 2.
</pre>

<p style="user-select: auto;"><strong class="example" style="user-select: auto;">Example 2:</strong></p>

<pre style="user-select: auto;"><strong style="user-select: auto;">Input:</strong> nums1 = [1,2,3,6], nums2 = [2,3,4,5]
<strong style="user-select: auto;">Output:</strong> 2
<strong style="user-select: auto;">Explanation:</strong> There are two common elements in the array 2 and 3 out of which 2 is the smallest, so 2 is returned.
</pre>

<p style="user-select: auto;">&nbsp;</p>
<p style="user-select: auto;"><strong style="user-select: auto;">Constraints:</strong></p>

<ul style="user-select: auto;">
	<li style="user-select: auto;"><code style="user-select: auto;">1 &lt;= nums1.length, nums2.length &lt;= 10<sup style="user-select: auto;">5</sup></code></li>
	<li style="user-select: auto;"><code style="user-select: auto;">1 &lt;= nums1[i], nums2[j] &lt;= 10<sup style="user-select: auto;">9</sup></code></li>
	<li style="user-select: auto;">Both <code style="user-select: auto;">nums1</code> and <code style="user-select: auto;">nums2</code> are sorted in <strong style="user-select: auto;">non-decreasing</strong> order.</li>
</ul>
</div>