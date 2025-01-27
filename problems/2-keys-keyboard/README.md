<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../dota2-senate "Dota2 Senate")
　　　　　　　　　　　　　　　　
[Next >](../4-keys-keyboard "4 Keys Keyboard")

## [650. 2 Keys Keyboard (Medium)](https://leetcode.com/problems/2-keys-keyboard "只有两个键的键盘")

<p>There is only one character <code>&#39;A&#39;</code> on the screen of a notepad. You can perform two operations on this notepad for each step:</p>

<ul>
	<li>Copy All: You can copy all the characters present on the screen (a partial copy is not allowed).</li>
	<li>Paste: You can paste the characters which are copied last time.</li>
</ul>

<p>Given an integer <code>n</code>, return <em>the minimum number of operations to get the character</em> <code>&#39;A&#39;</code> <em>exactly</em> <code>n</code> <em>times on the screen</em>.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> n = 3
<strong>Output:</strong> 3
<strong>Explanation:</strong> Intitally, we have one character &#39;A&#39;.
In step 1, we use Copy All operation.
In step 2, we use Paste operation to get &#39;AA&#39;.
In step 3, we use Paste operation to get &#39;AAA&#39;.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> n = 1
<strong>Output:</strong> 0
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 1000</code></li>
</ul>

### Related Topics
  [[Dynamic Programming](../../tag/dynamic-programming/README.md)]

### Similar Questions
  1. [4 Keys Keyboard](../4-keys-keyboard) (Medium)
  1. [Broken Calculator](../broken-calculator) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
How many characters may be there in the clipboard at the last step if n = 3? n = 7? n = 10? n = 24?
</details>
