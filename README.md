Download Link: https://assignmentchef.com/product/solved-cecs328-lab5
<br>
<strong>Programming assignment 5. </strong>

Part A

<strong><u>NOTE</u></strong>: You are <strong>NOT</strong> allowed to define a new array in any part of the code.

Create the following functions: <strong>build_MaxHeap</strong>, <strong>max_heapify, heap_sort</strong>.<strong>  </strong>

<ol>

 <li>Request the user to enter a positive integer, and call it <strong>n</strong>.</li>

 <li>Generate <strong>n</strong> random integers between <strong>-100 to 100</strong> and save them in array <strong>a</strong>.</li>

 <li>Call <strong>heap_sort </strong>function to sort the array. In order to sort the array using heapsort, you need to follow the below steps:</li>

</ol>

3.1 Build a max-heap (call the function build_Maxheap). In order to build the max-heap follow the below pseudocode:




% <em>new_a is the output of the function, if you are using any other programming language, please</em> write      % <em>return new_a at the end of your code.</em>

a = build_MaxHeap(a)   n = length(a);  for i=n:-1:1  %<em> i= n, n-1, n-2,.., 1, </em><em>Can  we start from n/2 instead of n? Why????</em> a(1:i) = max_heapify(a,i);  % a(1:i) = contains a[1] a[2] …a[i] (You could have a flag for the i too! (Assume that i is the index of the last element of the array! &#x1f60a;)




<h2>end</h2>




3.2 Keep removing the roots (first element in a) one by one until the tree/array becomes empty.




<ol start="4">

 <li>Determine the <strong>average-running time</strong> of <strong>heap_sort</strong> function for <strong>n=1000</strong>, and <strong>100 </strong></li>

 <li>Compare your answer with the average-running time of <u>selection sort</u> (<strong>you need implement it</strong>).</li>

</ol>




<h1>Part B</h1>

<ol>

 <li>Generate and print a random array of size 10.</li>

 <li>Call <em>heap_sort</em> to sort the numbers.</li>

 <li>Print the result.</li>

</ol>