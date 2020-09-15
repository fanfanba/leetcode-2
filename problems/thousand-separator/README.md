<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../bank-account-summary "Bank Account Summary")
　　　　　　　　　　　　　　　　
[Next >](../minimum-number-of-vertices-to-reach-all-nodes "Minimum Number of Vertices to Reach All Nodes")

## [1556. Thousand Separator (Easy)](https://leetcode.com/problems/thousand-separator "千位分隔数")

<p>Given an&nbsp;integer <code>n</code>, add a dot (&quot;.&quot;)&nbsp;as the thousands separator and return it in&nbsp;string format.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> n = 987
<strong>Output:</strong> &quot;987&quot;
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> n = 1234
<strong>Output:</strong> &quot;1.234&quot;
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> n = 123456789
<strong>Output:</strong> &quot;123.456.789&quot;
</pre>

<p><strong>Example 4:</strong></p>

<pre>
<strong>Input:</strong> n = 0
<strong>Output:</strong> &quot;0&quot;
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>0 &lt;= n &lt; 2^31</code></li>
</ul>

### Related Topics
  [[String](../../tag/string/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Scan from the back of the integer and use dots to connect blocks with length 3 except the last block.
</details>