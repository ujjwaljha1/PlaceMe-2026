<!-- Markdown content below -->

# 📚 CSE - Mock Test - 04 🚀

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

**Test ID:** `64230b6b435752a6709213f1` :id:
**Total Questions:** `20` 🧮
**Total Time:** `35 minutes` :hourglass_flowing_sand:

---

## 🔥 Question 1 🧠 🤔

Assume that the algorithms considered here sort the input sequences in ascending order. If the input is already in ascending order, which of the following are TRUE?
I.   Quicksort runs in Θ(n<sup>2</sup>) time
II.  Bubblesort runs in Θ(n<sup>2</sup>) time
III. Mergesort runs in  Θ(n) time
IV.  Insertion sort runs in  Θ(n) time_

### 📋 Options:
- A. 🟢 I and IV only
- B. 🔴 I and II only
- C. 🔴 I and III only
- D. 🔴 II and IV only

**⭐ Correct Answer:** 🎯 `I and IV only`

✨ --- ✨ --- ✨

## 🔥 Question 2 🧠 🤔

Consider the C function given below. Assume that the array listA contains n (&gt; 0) elements, sorted in ascending order.
int ProcessArray(int *listA, int x, int n)
{
int i, j, k;
i = 0;
j = n-1;
do
{
k = (i+j)/2;
if (x &lt;= listA[k])
j = k-1;
if (listA[k] &lt;= x)
i = k+1;
}
while (i &lt;= j);
if (listA[k] == x)
return(k);
else
return -1;
}
Which one of the following statements about the function ProcessArray is CORRECT?_

### 📋 Options:
- A. 🔴 It will return −1 even when x is present in listA.
- B. 🔴 It will always find the maximum element in listA.
- C. 🟢 It is an implementation of binary search.
- D. 🔴 It will run into an infinite loop when x is not in listA.

**⭐ Correct Answer:** 🎯 `It is an implementation of binary search.`

✨ --- ✨ --- ✨

## 🔥 Question 3 🧠 🤔

Time required to merge two sorted lists of size m and n, is_

### 📋 Options:
- A. 🔴 Ο(m log n)
- B. 🔴 Ο(m | n)
- C. 🟢 Ο(m + n)
- D. 🔴 Ο(n log m)

**⭐ Correct Answer:** 🎯 `Ο(m + n)`

✨ --- ✨ --- ✨

## 🔥 Question 4 🧠 🤔

Which of the following is/are property/properties of a dynamic programming problem?_

### 📋 Options:
- A. 🔴 Greedy approach
- B. 🟢 Both optimal substructure and overlapping sub problems
- C. 🔴 Optimal substructure
- D. 🔴 Overlapping sub problems

**⭐ Correct Answer:** 🎯 `Both optimal substructure and overlapping sub problems`

✨ --- ✨ --- ✨

## 🔥 Question 5 🧠 🤔

What is the best time complexity of bubble sort?_

### 📋 Options:
- A. 🔴 NlogN
- B. 🟢 N
- C. 🔴 N^2
- D. 🔴 N(logN)^2

**⭐ Correct Answer:** 🎯 `N`

✨ --- ✨ --- ✨

## 🔥 Question 6 🧠 🤔

What is a randomized Quick Sort?_

### 📋 Options:
- A. 🟢 Any element in the array is chosen as the pivot
- B. 🔴 The rightmost element is chosen as the pivot
- C. 🔴 A random number is generated which is used as the pivot
- D. 🔴 The leftmost element is chosen as the pivot

**⭐ Correct Answer:** 🎯 `Any element in the array is chosen as the pivot`

✨ --- ✨ --- ✨

## 🔥 Question 7 🧠 🤔

In conversion from prefix to postfix using stack data-structure, if operators and operands are pushed and popped exactly once, then the run-time complexity is −_

### 📋 Options:
- A. 🔴 Ο(log n)
- B. 🔴 Ο(n2)
- C. 🔴 Ο(1)
- D. 🟢 Ο(n)

**⭐ Correct Answer:** 🎯 `Ο(n)`

✨ --- ✨ --- ✨

## 🔥 Question 8 🧠 🤔

Consider an array of elements arr[5]= {5,4,3,2,1} , what are the steps of insertions done while doing insertion sort in the array._

### 📋 Options:
- A. 🔴 4 5 3 2 1  
2 3 4 5 1   
3 4 5 2 1    
1 2 3 4 5
- B. 🟢 4 5 3 2 1   
3 4 5 2 1  
2 3 4 5 1  
1 2 3 4 5
- C. 🔴 5 4 3 1 2  
5 4 1 2 3  
5 1 2 3 4   
1 2 3 4 5
- D. 🔴 4 3 2 1 5  
3 2 1 5 4  
2 1 5 4 3    
1 5 4 3 2

**⭐ Correct Answer:** 🎯 `4 5 3 2 1   
3 4 5 2 1  
2 3 4 5 1  
1 2 3 4 5`

✨ --- ✨ --- ✨

## 🔥 Question 9 🧠 🤔

In a modified merge sort, the input array is splited at a position one-third of the length(N) of the array. What is the worst case time complexity of this merge sort?_

### 📋 Options:
- A. 🟢 N(logN base 3/2)
- B. 🔴 N(logN base 2/3)
- C. 🔴 N(logN base 3)
- D. 🔴 N(logN base 1/3)

**⭐ Correct Answer:** 🎯 `N(logN base 3/2)`

✨ --- ✨ --- ✨

## 🔥 Question 10 🧠 🤔

Which is the correct order of the following algorithms with respect to their time Complexity in the best case?_

### 📋 Options:
- A. 🔴 Merge sort &gt; Quick sort &gt;Insertion sort &gt; selection sort
- B. 🟢 insertion sort &lt; Quick sort &lt; Merge sort &lt; selection sort
- C. 🔴 Merge sort &gt; selection sort &gt; quick sort &gt; insertion sort
- D. 🔴 Merge sort &gt; Quick sort &gt; selection sort &gt; insertion sort

**⭐ Correct Answer:** 🎯 `insertion sort &lt; Quick sort &lt; Merge sort &lt; selection sort`

✨ --- ✨ --- ✨

## 🔥 Question 11 🧠 🤔

The worst case running times of Insertion sort, Merge sort and Quick sort, respectively, are:_

### 📋 Options:
- A. 🔴 Θ(n<sup>2</sup>), Θ(n log n) and Θ(n log n)
- B. 🟢 Θ(n<sup>2</sup>), Θ(n log n) and Θ(n<sup>2</sup>)
- C. 🔴 Θ(n<sup>2</sup>), Θ(n<sup>2</sup>) and Θ(n Log n)
- D. 🔴 Θ(n log n), Θ(n log n) and Θ(n<sup>2</sup>)

**⭐ Correct Answer:** 🎯 `Θ(n<sup>2</sup>), Θ(n log n) and Θ(n<sup>2</sup>)`

✨ --- ✨ --- ✨

## 🔥 Question 12 🧠 🤔

Which of the following is not true about Quick Sort?_

### 📋 Options:
- A. 🔴 in-place algorithm
- B. 🔴 can be implemented as a stable sort
- C. 🟢 pivot position can be changed
- D. 🔴 adaptive sorting algorithm

**⭐ Correct Answer:** 🎯 `pivot position can be changed`

✨ --- ✨ --- ✨

## 🔥 Question 13 🧠 🤔

Consider the following program fragment for reversing the digits in a given integer to obtain a new integer. Let n = D1D2…Dm
int n, rev;
rev = 0;
while (n &gt; 0)
{
rev = rev*10 + n%10;
n = n/10;
}
The loop invariant condition at the end of the ith iteration is:_

### 📋 Options:
- A. 🔴 n = D1D2….Dm and rev = DmDm-1…D2D1
- B. 🔴 n = Dm-i+1…Dm-1Dm and rev = Dm-1….D2D1
- C. 🔴 n != rev
- D. 🟢 n = D1D2….Dm-i and rev = DmDm-1…Dm-i+1

**⭐ Correct Answer:** 🎯 `n = D1D2….Dm-i and rev = DmDm-1…Dm-i+1`

✨ --- ✨ --- ✨

## 🔥 Question 14 🧠 🤔

Which of the following condition is sufficient to detect cycle in a directed graph?_

### 📋 Options:
- A. 🔴 None of the above
- B. 🟢 There is an edge from currently being visited node to an ancestor of currently visited node in DFS forest.
- C. 🔴 There is an edge from currently being visited node to an already visited node.
- D. 🔴 Every node is seen twice in DFS.

**⭐ Correct Answer:** 🎯 `There is an edge from currently being visited node to an ancestor of currently visited node in DFS forest.`

✨ --- ✨ --- ✨

## 🔥 Question 15 🧠 🤔

What are the appropriate data structures for following algorithms?
1) Breadth First Search
2) Depth First Search
3) Prim's Minimum Spanning Tree
4) Kruskal' Minimum Spanning Tree_

### 📋 Options:
- A. 🔴 1) Stack
2) Queue
3) Union Find
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">4) Priority Queue
- B. 🟢 1) Queue
2) Stack
3) Priority Queue
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">4) Union Find
- C. 🔴 1) Stack
2) Queue
3) Priority Queue
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">4) Union Find
- D. 🔴 1) Priority Queue
2) Queue
3) Stack
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">4) Union Find

**⭐ Correct Answer:** 🎯 `1) Queue
2) Stack
3) Priority Queue
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">4) Union Find`

✨ --- ✨ --- ✨

## 🔥 Question 16 🧠 🤔

Let G be an undirected graph. Consider a depth-first traversal of G, and let T be the resulting depth-first search tree. Let u be a vertex in G and let v be the first new (unvisited) vertex visited after visiting u in the traversal. Which of the following statements is always true?_

### 📋 Options:
- A. 🔴 {u,v} must be an edge in G, and u is a descendant of v in T
- B. 🔴 If {u,v} is not an edge in G then u and v must have the same parent in T
- C. 🔴 {u,v} must be an edge in G, and v is a descendant of u in T
- D. 🟢 If {u,v} is not an edge in G then u is a leaf in T

**⭐ Correct Answer:** 🎯 `If {u,v} is not an edge in G then u is a leaf in T`

✨ --- ✨ --- ✨

## 🔥 Question 17 🧠 🤔

Which of the following is correct recurrence for worst case of Binary Search?_

### 📋 Options:
- A. 🟢 T(n) = T(n/2) + O(1) and T(1) = T(0) = O(1)
- B. 🔴 T(n) = T(n-1) + O(1) and T(1) = T(0) = O(1)
- C. 🔴 T(n) = 2T(n/2) + O(1) and T(1) = T(0) = O(1)
- D. 🔴 T(n) = T(n-2) + O(1) and T(1) = T(0) = O(1)

**⭐ Correct Answer:** 🎯 `T(n) = T(n/2) + O(1) and T(1) = T(0) = O(1)`

✨ --- ✨ --- ✨

## 🔥 Question 18 🧠 🤔

Consider the following recursive C function that takes two arguments
unsigned int foo(unsigned int n, unsigned int r) {
if (n  &gt; 0) return (n%r +  foo (n/r, r ));
else return 0;
}
What is the return value of the function foo when it is called as foo(345, 10) ?_

### 📋 Options:
- A. 🟢 12
- B. 🔴 345
- C. 🔴 5
- D. 🔴 3

**⭐ Correct Answer:** 🎯 `12`

✨ --- ✨ --- ✨

## 🔥 Question 19 🧠 🤔

For the given graph(G), which of the following statements is true?
<a href="https://www.sanfoundry.com/wp-content/uploads/2017/08/data-structure-questions-answers-graph-q3.png"><span style=""><img alt="data-structure-questions-answers-graph-q3" border="0" height="106" id="Picture 7" src="https://hub.myperfectice.com/uploads/image/58dde32f02806f00011effc4/ye05r0/31402daa-eaa7-490a-ab3f-e0b9270b9bb7.jpg" width="115"/></span></a>_

### 📋 Options:
- A. 🔴 The edge connectivity of the graph is 1
- B. 🔴 G is not a connected graph
- C. 🟢 The vertex connectivity of the graph is 2
- D. 🔴 G is a complete graph

**⭐ Correct Answer:** 🎯 `The vertex connectivity of the graph is 2`

✨ --- ✨ --- ✨

## 🔥 Question 20 🧠 🤔

Consider the same recursive C function that takes two arguments
unsigned int foo(unsigned int n, unsigned int r) {
if (n  &gt; 0) return (n%r +  foo (n/r, r ));
else return 0;
}
What is the return value of the function foo when it is called as foo(513, 2)?_

### 📋 Options:
- A. 🔴 9
- B. 🔴 8
- C. 🟢 2
- D. 🔴 5

**⭐ Correct Answer:** 🎯 `2`

✨ --- ✨ --- ✨

## :sos: Need Help? ✋

💬 If you encounter any issues or have questions, please don't hesitate to reach out!

🔗 [Report an Issue](https://example.com/report-issue)

![Thank You](https://media.giphy.com/media/3o6Zt6KHxJTbXCnSvu/giphy.gif)

:clock10: *Last updated: 2024-07-22 18:07:43*
