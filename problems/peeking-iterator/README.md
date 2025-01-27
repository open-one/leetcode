<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../move-zeroes "Move Zeroes")
　　　　　　　　　　　　　　　　
[Next >](../inorder-successor-in-bst "Inorder Successor in BST")

## [284. Peeking Iterator (Medium)](https://leetcode.com/problems/peeking-iterator "顶端迭代器")

<p>Design an iterator that supports the <code>peek</code> operation on a list in addition to the <code>hasNext</code> and the <code>next</code> operations.</p>

<p>Implement the <code>PeekingIterator</code> class:</p>

<ul>
	<li><code>PeekingIterator(int[] nums)</code> Initializes the object with the given integer array <code>nums</code>.</li>
	<li><code>int next()</code> Returns the next element in the array and moves the pointer to the next element.</li>
	<li><code>bool hasNext()</code> Returns <code>true</code> if there are still elements in the array.</li>
	<li><code>int peek()</code> Returns the next element in the array <strong>without</strong> moving the pointer.</li>
</ul>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input</strong>
[&quot;PeekingIterator&quot;, &quot;next&quot;, &quot;peek&quot;, &quot;next&quot;, &quot;next&quot;, &quot;hasNext&quot;]
[[[1, 2, 3]], [], [], [], [], []]
<strong>Output</strong>
[null, 1, 2, 2, 3, false]

<strong>Explanation</strong>
PeekingIterator peekingIterator = new PeekingIterator([1, 2, 3]); // [<u><strong>1</strong></u>,2,3]
peekingIterator.next();    // return 1, the pointer moves to the next element [1,<u><strong>2</strong></u>,3].
peekingIterator.peek();    // return 2, the pointer does not move [1,<u><strong>2</strong></u>,3].
peekingIterator.next();    // return 2, the pointer moves to the next element [1,2,<u><strong>3</strong></u>]
peekingIterator.next();    // return 3, the pointer moves to the next element [1,2,3]
peekingIterator.hasNext(); // return False
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 1000</code></li>
	<li><code>1 &lt;= nums[i] &lt;= 1000</code></li>
	<li>All the calls to <code>next</code> and <code>peek</code> are valid.</li>
	<li>At most <code>1000</code> calls will be made to <code>next</code>, <code>hasNext</code>, and <code>peek</code>.</li>
</ul>

<p>&nbsp;</p>
<strong>Follow up:</strong> How would you extend your design to be generic and work with all types, not just integer?

### Related Topics
  [[Design](../../tag/design/README.md)]

### Similar Questions
  1. [Binary Search Tree Iterator](../binary-search-tree-iterator) (Medium)
  1. [Flatten 2D Vector](../flatten-2d-vector) (Medium)
  1. [Zigzag Iterator](../zigzag-iterator) (Medium)

### Hints
<details>
<summary>Hint 1</summary>
Think of "looking ahead". You want to cache the next element.
</details>

<details>
<summary>Hint 2</summary>
Is one variable sufficient? Why or why not?
</details>

<details>
<summary>Hint 3</summary>
Test your design with call order of <code>peek()</code> before <code>next()</code> vs <code>next()</code> before <code>peek()</code>.
</details>

<details>
<summary>Hint 4</summary>
For a clean implementation, check out <a href="https://github.com/google/guava/blob/703ef758b8621cfbab16814f01ddcc5324bdea33/guava-gwt/src-super/com/google/common/collect/super/com/google/common/collect/Iterators.java#L1125" target="_blank">Google's guava library source code</a>.
</details>
