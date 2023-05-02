Download Link: https://assignmentchef.com/product/solved-cis575-assignment-4
<br>
<ol>

 <li>Consider the following program (which may be what you constructed in Assignment 1) whose running time <em>T</em>(<em>n</em>) we want to estimate, as a function of <em>n </em>= <em>hi </em>− <em>lo</em>:</li>

</ol>

Find(<em>x,A,lo,hi</em>)

<em>q </em>← (<em>lo </em>+ <em>hi</em>) div 2 <strong>if </strong><em>A</em>[<em>q</em>] = <em>x </em><strong>return </strong><em>q</em>

<strong>else if </strong><em>A</em>[<em>q</em>] <em>&lt; x </em><strong>return </strong>Find(<em>x,A,q </em>+ 1<em>,hi</em>) <strong>else return </strong>Find(<em>x,A,lo,q </em>− 1)

<ol>

 <li>Write a recurrence for <em>T</em>(<em>n</em>). (You may assume arithmetic operations take time in Θ(1).)</li>

 <li>Solve that recurrence, by using the “Master Theorem”. (You should indicate which version you use, and what are the given values of <em>a</em>, <em>b</em>, etc)</li>

</ol>

<ol start="2">

 <li>Solve each of the recurrences</li>

</ol>

(1)

(2)

(3)

Your answers should be of the form <em>T</em>(<em>n</em>) ∈ Θ(<em>f</em>(<em>n</em>)), with <em>f </em>as simple as possible. You should justify your answers, for example by appealing to the “Master Theorem” (if applicable).

<ol start="3">

 <li>Given real numbers <em>s,u </em>with 0 <em>&lt; s </em>≤ <em>u </em>≤ 0<em>.</em>8, consider the function <em>T </em>given by</li>

</ol>

<em>T</em>(<em>n</em>)     =     2<em>n                                           </em>for <em>n </em>≤ 4

<em>T</em>(<em>n</em>)     =      <em>T</em>(d<em>sn</em>e) + <em>T</em>(d<em>un</em>e) + 1        for <em>n </em>≥ 5

This is well-defined, since when <em>n </em>≥ 5 then <em>n </em>− <em>un </em>= (1 − <em>u</em>)<em>n </em>≥ 0<em>.</em>2<em>n </em>≥ 1 and thus d<em>sn</em>e≤d<em>un</em>e <em>&lt; n</em>.

<ol>

 <li>Tabulate <em>T</em>(<em>n</em>), for <em>n </em>from 1 to 10, with <em>s </em>= <em>u </em>= 0<em>.</em>6, and also with <em>s </em>= 0<em>.</em>6 and <em>u </em>= 0<em>.</em></li>

 <li>Use the <em>substitution method </em>to find a constraint on the values of <em>s </em>and <em>u </em>such that you can prove by induction in <em>n </em>that</li>

</ol>

<em>T</em>(<em>n</em>) ≥ <em>cn</em><sup>2 </sup>for all <em>n </em>≥ 0

for some positive real number <em>c</em>; list the <em>largest c </em>that will work.

<ol start="3">

 <li>Compare your “experimental” results from part 1 to your “theoretical” results from part 2. That is, for <em>s </em>= <em>u </em>= 0<em>.</em>6 and also for <em>s </em>= 0<em>.</em>6<em>,u </em>= 0<em>.</em>8, tell whether the constraint from part 2 is satisfied; if so, with <em>c </em>the constant you found in part 2, tell whether <em>T</em>(<em>n</em>) ≥ <em>cn</em><sup>2 </sup>does indeed hold for all <em>n </em>≤ 10.</li>

</ol>