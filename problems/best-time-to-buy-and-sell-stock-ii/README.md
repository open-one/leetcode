<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../best-time-to-buy-and-sell-stock "Best Time to Buy and Sell Stock")
　　　　　　　　　　　　　　　　
[Next >](../best-time-to-buy-and-sell-stock-iii "Best Time to Buy and Sell Stock III")

## [122. Best Time to Buy and Sell Stock II (Easy)](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii "买卖股票的最佳时机 II")

<p>You are given an array <code>prices</code> where <code>prices[i]</code> is the price of a given stock on the <code>i<sup>th</sup></code> day.</p>

<p>Find the maximum profit you can achieve. You may complete as many transactions as you like (i.e., buy one and sell one share of the stock multiple times).</p>

<p><strong>Note:</strong> You may not engage in multiple transactions simultaneously (i.e., you must sell the stock before you buy again).</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> prices = [7,1,5,3,6,4]
<strong>Output:</strong> 7
<strong>Explanation:</strong> Buy on day 2 (price = 1) and sell on day 3 (price = 5), profit = 5-1 = 4.
Then buy on day 4 (price = 3) and sell on day 5 (price = 6), profit = 6-3 = 3.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> prices = [1,2,3,4,5]
<strong>Output:</strong> 4
<strong>Explanation:</strong> Buy on day 1 (price = 1) and sell on day 5 (price = 5), profit = 5-1 = 4.
Note that you cannot buy on day 1, buy on day 2 and sell them later, as you are engaging multiple transactions at the same time. You must sell before buying again.
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> prices = [7,6,4,3,1]
<strong>Output:</strong> 0
<strong>Explanation:</strong> In this case, no transaction is done, i.e., max profit = 0.
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= prices.length &lt;= 3 * 10<sup>4</sup></code></li>
	<li><code>0 &lt;= prices[i] &lt;= 10<sup>4</sup></code></li>
</ul>

### Related Topics
  [[Greedy](../../tag/greedy/README.md)]
  [[Array](../../tag/array/README.md)]

### Similar Questions
  1. [Best Time to Buy and Sell Stock](../best-time-to-buy-and-sell-stock) (Easy)
  1. [Best Time to Buy and Sell Stock III](../best-time-to-buy-and-sell-stock-iii) (Hard)
  1. [Best Time to Buy and Sell Stock IV](../best-time-to-buy-and-sell-stock-iv) (Hard)
  1. [Best Time to Buy and Sell Stock with Cooldown](../best-time-to-buy-and-sell-stock-with-cooldown) (Medium)
  1. [Best Time to Buy and Sell Stock with Transaction Fee](../best-time-to-buy-and-sell-stock-with-transaction-fee) (Medium)
