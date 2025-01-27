<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../make-two-arrays-equal-by-reversing-sub-arrays "Make Two Arrays Equal by Reversing Sub-arrays")
　　　　　　　　　　　　　　　　
[Next >](../course-schedule-iv "Course Schedule IV")

## [1461. Check If a String Contains All Binary Codes of Size K (Medium)](https://leetcode.com/problems/check-if-a-string-contains-all-binary-codes-of-size-k "检查一个字符串是否包含所有长度为 K 的二进制子串")

<p>Given a binary string <code>s</code> and an integer <code>k</code>.</p>

<p>Return <code>true</code> <em>if every binary code of length</em> <code>k</code> <em>is a substring of</em> <code>s</code>. Otherwise, return <code>false</code>.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;00110110&quot;, k = 2
<strong>Output:</strong> true
<strong>Explanation:</strong> The binary codes of length 2 are &quot;00&quot;, &quot;01&quot;, &quot;10&quot; and &quot;11&quot;. They can be all found as substrings at indicies 0, 1, 3 and 2 respectively.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;00110&quot;, k = 2
<strong>Output:</strong> true
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;0110&quot;, k = 1
<strong>Output:</strong> true
<strong>Explanation:</strong> The binary codes of length 1 are &quot;0&quot; and &quot;1&quot;, it is clear that both exist as a substring. 
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;0110&quot;, k = 2
<strong>Output:</strong> false
<strong>Explanation:</strong> The binary code &quot;00&quot; is of length 2 and doesn&#39;t exist in the array.
</pre>

<p><strong>Example 5:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;0000000001011100&quot;, k = 4
<strong>Output:</strong> false
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;= 5 * 10<sup>5</sup></code></li>
	<li><code>s[i]</code> is either <code>&#39;0&#39;</code> or <code>&#39;1&#39;</code>.</li>
	<li><code>1 &lt;= k &lt;= 20</code></li>
</ul>

### Related Topics
  [[Bit Manipulation](../../tag/bit-manipulation/README.md)]
  [[String](../../tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
We need only to check all sub-strings of length k.
</details>

<details>
<summary>Hint 2</summary>
The number of distinct sub-strings should be exactly 2^k.
</details>
