<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../prime-number-of-set-bits-in-binary-representation "Prime Number of Set Bits in Binary Representation")
　　　　　　　　　　　　　　　　
[Next >](../largest-plus-sign "Largest Plus Sign")

## [763. Partition Labels (Medium)](https://leetcode.com/problems/partition-labels "划分字母区间")

<p>A string <code>s</code> of lowercase English letters is given. We want to partition this string into as many parts as possible so that each letter appears in at most one part, and return a list of integers representing the size of these parts.</p>

<p>&nbsp;</p>

<p><b>Example 1:</b></p>

<pre>
<b>Input:</b> s = &quot;ababcbacadefegdehijhklij&quot;
<b>Output:</b> [9,7,8]
<b>Explanation:</b>
The partition is &quot;ababcbaca&quot;, &quot;defegde&quot;, &quot;hijhklij&quot;.
This is a partition so that each letter appears in at most one part.
A partition like &quot;ababcbacadefegde&quot;, &quot;hijhklij&quot; is incorrect, because it splits s into less parts.
</pre>

<p>&nbsp;</p>

<p><b>Note:</b></p>

<ul>
	<li><code>s</code> will have length in range <code>[1, 500]</code>.</li>
	<li><code>s</code> will consist of lowercase English letters (<code>&#39;a&#39;</code> to <code>&#39;z&#39;</code>) only.</li>
</ul>

<p>&nbsp;</p>

### Related Topics
  [[Greedy](../../tag/greedy/README.md)]
  [[Two Pointers](../../tag/two-pointers/README.md)]

### Similar Questions
  1. [Merge Intervals](../merge-intervals) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
Try to greedily choose the smallest partition that includes the first letter.  If you have something like "abaccbdeffed", then you might need to add b.  You can use an map like "last['b'] = 5" to help you expand the width of your partition.
</details>
