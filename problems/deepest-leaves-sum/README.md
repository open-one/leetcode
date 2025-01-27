<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../number-of-paths-with-max-score "Number of Paths with Max Score")
　　　　　　　　　　　　　　　　
[Next >](../find-the-team-size "Find the Team Size")

## [1302. Deepest Leaves Sum (Medium)](https://leetcode.com/problems/deepest-leaves-sum "层数最深叶子节点的和")

Given the <code>root</code> of a binary tree, return <em>the sum of values of its deepest leaves</em>.
<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2019/07/31/1483_ex1.png" style="width: 273px; height: 265px;" />
<pre>
<strong>Input:</strong> root = [1,2,3,4,5,null,6,7,null,null,null,null,8]
<strong>Output:</strong> 15
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> root = [6,7,8,2,7,1,3,9,null,1,4,null,null,null,5]
<strong>Output:</strong> 19
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li>The number of nodes in the tree is in the range <code>[1, 10<sup>4</sup>]</code>.</li>
	<li><code>1 &lt;= Node.val &lt;= 100</code></li>
</ul>

### Related Topics
  [[Tree](../../tag/tree/README.md)]
  [[Depth-first Search](../../tag/depth-first-search/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Traverse the tree to find the max depth.
</details>

<details>
<summary>Hint 2</summary>
Traverse the tree again to compute the sum required.
</details>
