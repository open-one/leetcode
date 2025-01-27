<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../check-if-number-is-a-sum-of-powers-of-three "Check if Number is a Sum of Powers of Three")
　　　　　　　　　　　　　　　　
[Next >](../count-pairs-of-nodes "Count Pairs Of Nodes")

## [1781. Sum of Beauty of All Substrings (Medium)](https://leetcode.com/problems/sum-of-beauty-of-all-substrings "所有子字符串美丽值之和")

<p>The <strong>beauty</strong> of a string is the difference in frequencies between the most frequent and least frequent characters.</p>

<ul>
	<li>For example, the beauty of <code>&quot;abaacc&quot;</code> is <code>3 - 1 = 2</code>.</li>
</ul>

<p>Given a string <code>s</code>, return <em>the sum of <strong>beauty</strong> of all of its substrings.</em></p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;aabcb&quot;
<strong>Output:</strong> 5
<strong>Explanation: </strong>The substrings with non-zero beauty are [&quot;aab&quot;,&quot;aabc&quot;,&quot;aabcb&quot;,&quot;abcb&quot;,&quot;bcb&quot;], each with beauty equal to 1.</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;aabcbaa&quot;
<strong>Output:</strong> 17
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= s.length &lt;=<sup> </sup>500</code></li>
	<li><code>s</code> consists of only lowercase English letters.</li>
</ul>

### Related Topics
  [[Hash Table](../../tag/hash-table/README.md)]
  [[String](../../tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Maintain a prefix sum for the frequencies of characters.
</details>

<details>
<summary>Hint 2</summary>
You can iterate over all substring then iterate over the alphabet and find which character appears most and which appears least using the prefix sum array
</details>
