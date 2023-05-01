Download Link: https://assignmentchef.com/product/solved-ch231a-assignment4-merge-sort
<br>
<h1></h1>

<ul>

 <li> Implement a variant of Merge Sort that does not divide the problem all the waydown to subproblems of size 1. Instead, when reaching subsequences of length <em>k </em>it applies Insertion Sort on these <em>n/k </em></li>

 <li> Apply it to the different sequences which satisfy best case, worst case and averagecase for different values of <em>k</em>. Plot the execution times for different values of <em>k</em>.</li>

 <li>How do the different values of <em>k </em>change the best-, average-, and worst-case asymptotic time complexities for this variant? Explain/prove your answer.</li>

</ul>

<ul>

 <li><strong>Bonus  </strong>Based on the results from (b) and (c), how would you choose <em>k </em>in practice? Briefly explain.</li>

</ul>

<h2><strong>Problem 4.2 </strong>Recurrences</h2>

Use the substitution method, the recursion tree, or the master theorem method to derive upper and lower bounds for <em>T</em>(<em>n</em>) in each of the following recurrences. Make the bounds as tight as possible. Assume that <em>T</em>(<em>n</em>) is constant for <em>n</em>≤ 2.

<ul>

 <li><em>T</em>(<em>n</em>) = 36<em>T</em>(<em>n/</em>6) + 2<em>n</em>,</li>

 <li><em>T</em>(<em>n</em>) = 5<em>T</em>(<em>n/</em>3) + 17<em>n</em><sup>1<em>.</em>2</sup>,</li>

 <li><em>T</em>(<em>n</em>) = 12<em>T</em>(<em>n/</em>2) + <em>n</em><sup>2 </sup>lg<em>n</em>,</li>

 <li><em>T</em>(<em>n</em>) = 3<em>T</em>(<em>n/</em>5) + <em>T</em>(<em>n/</em>2) + 2<em><sup>n</sup></em>,</li>

 <li><strong>Bonus </strong> <em>T</em>(<em>n</em>) = <em>T</em>(2<em>n/</em>5) + <em>T</em>(3<em>n/</em>5) + Θ(<em>n</em>).</li>

</ul>