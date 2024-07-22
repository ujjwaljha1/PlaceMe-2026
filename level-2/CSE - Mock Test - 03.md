# 📚 CSE - Mock Test - 03

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

## Test Information

- **Test ID:** `64230b63435752f6c4920ccc`
- **Number of Questions:** `20`
- **Time Limit:** `35 minutes`

---

## Question 1
What is the best time complexity of bubble sort?

### Options:

A. ❌ N(logN)^2
B. ✅ N
C. ❌ N * logN
D. ❌ N^2
**Correct Answer:** N

---

## Question 2
Traversal of a graph is different from tree because

### Options:

A. ✅ There can be a loop in graph so we must maintain a visited flag for every vertex
B. ❌ BFS of a graph uses queue, but a time efficient BFS of a tree is recursive.
C. ❌ All of the above
D. ❌ DFS of a graph uses stack, but inorder traversal of a tree is recursive
**Correct Answer:** There can be a loop in graph so we must maintain a visited flag for every vertex

---

## Question 3
What is recurrence for worst case of Quick Sort and what is the time complexity in Worst case?

### Options:

A. ❌ Recurrence is T(n) = 2T(n/2) + O(n) and time complexity is O(nLogn)
B. ❌ Recurrence is T(n) = T(n/10) + T(9n/10) + O(n) and time complexity is O(nLogn)
C. ✅ Recurrence is T(n) = T(n-1) + O(n) and time complexity is O(n^2)
D. ❌ Recurrence is T(n) = T(n-2) + O(n) and time complexity is O(n^2)
**Correct Answer:** Recurrence is T(n) = T(n-1) + O(n) and time complexity is O(n^2)

---

## Question 4
A graph with all vertices having equal degree is known as a __________

### Options:

A. ✅ Regular Graph
B. ❌ Multi Graph
C. ❌ Complete Graph
D. ❌ Simple Graph
**Correct Answer:** Regular Graph

---

## Question 5
Which of the following algorithm can be used to <b>efficiently </b>calculate single source shortest paths in a Directed Acyclic Graph?

### Options:

A. ❌ Strongly Connected Component
B. ❌ Bellman-Ford
C. ❌ Dijkastra
D. ✅ Topological Sort
**Correct Answer:** Topological Sort

---

## Question 6
The worst case running times of Insertion sort, Merge sort and Quick sort, respectively, are:

### Options:

A. ❌ Θ(n log n), Θ(n log n) and Θ(n2)
B. ✅ Θ(n2), Θ(n log n) and Θ(n2)
C. ❌ Θ(n2), Θ(n2) and Θ(n Log n)
D. ❌ Θ(n2), Θ(n log n) and Θ(n log n)
**Correct Answer:** Θ(n2), Θ(n log n) and Θ(n2)

---

## Question 7
Suppose we are sorting an array of eight integers using quicksort, and we have just finished the first partitioning with the array looking like this:
2 5 1 7 9 12 11 10
Which statement is correct?

### Options:

A. ✅ The pivot could be either the 7 or the 9.
B. ❌ The pivot could be the 7, but it is not the 9
C. ❌ The pivot is not the 7, but it could be the 9
D. ❌ Neither the 7 nor the 9 is the pivot.
**Correct Answer:** The pivot could be either the 7 or the 9.

---

## Question 8
When a top-down approach of dynamic programming is applied to a problem, it usually _____________

### Options:

A. ❌ Decreases both, the time complexity and the space complexity
B. ✅ Decreases the time complexity and increases the space complexity
C. ❌ Increases the time complexity and decreases the space complexity
D. ❌ Increases both, the time complexity and the space complexity
**Correct Answer:** Decreases the time complexity and increases the space complexity

---

## Question 9
Output of following program?
#include&lt;stdio.h&gt;
void print(int n)
{
if (n &gt; 4000)
return;
printf("%d ", n);
print(2*n);
printf("%d ", n);
}
int main()
{
print(1000);
getchar();
return 0;
}

### Options:

A. ❌ 1000 2000 2000 1000
B. ❌ 1000 2000 4000 2000 1000
C. ❌ 1000 2000 4000
D. ✅ 1000 2000 4000 4000 2000
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">1000
**Correct Answer:** 1000 2000 4000 4000 2000
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">1000

---

## Question 10
To implement Dijkstra’s shortest path algorithm on unweighted graphs so that it runs in linear time, the data structure to be used is:

### Options:

A. ✅ Queue
B. ❌ B-Tree
C. ❌ Stack
D. ❌ Heap
**Correct Answer:** Queue

---

## Question 11
Which of the following is not true about comparison based sorting algorithms?

### Options:

A. ❌ The minimum possible time complexity of a comparison based sorting algorithm is O(nLogn) for a random input array
B. ❌ Counting Sort is not a comparison based sorting algorithm
C. ✅ Heap Sort is not a comparison based sorting algorithm.
D. ❌ Any comparison based sorting algorithm can be made stable by using position as a criteria when two elements are compared
**Correct Answer:** Heap Sort is not a comparison based sorting algorithm.

---

## Question 12
Which of the following algorithms is NOT a divide &amp; conquer algorithm by nature?

### Options:

A. ✅ Heap Sort
B. ❌ Quick Sort
C. ❌ Euclidean algorithm to compute the greatest common divisor
D. ❌ Cooley-Tukey fast Fourier transform
**Correct Answer:** Heap Sort

---

## Question 13
What is time complexity of fun()?
int fun(int n)
{
int count = 0;
for (int i = n; i &gt; 0; i /= 2)
for (int j = 0; j &lt; i; j++)
count += 1;
return count;
}

### Options:

A. ✅ O(n)
B. ❌ O(nLognLogn)
C. ❌ O(n^2)
D. ❌ O(nLogn)
**Correct Answer:** O(n)

---

## Question 14
Consider a situation where swap operation is very costly. Which of the following sorting algorithms should be preferred so that the number of swap operations are minimized in general?

### Options:

A. ✅ Selection Sort
B. ❌ Heap Sort
C. ❌ Merge Sort
D. ❌ Insertion Sort
**Correct Answer:** Selection Sort

---

## Question 15
What is the worst case time complexity of insertion sort where position of the data to be inserted is calculated using binary search?

### Options:

A. ❌ N(logN)^2
B. ✅ N^2
C. ❌ N
D. ❌ NlogN
**Correct Answer:** N^2

---

## Question 16
Which of the following is not a stable sorting algorithm in its typical implementation?

### Options:

A. ✅ Quick Sort
B. ❌ Bubble Sort
C. ❌ Inserting Sort
D. ❌ Merge Sort
**Correct Answer:** Quick Sort

---

## Question 17
What is the number of edges present in a complete graph having n vertices?

### Options:

A. ❌ (n*(n+1))/2
B. ❌ n
C. ✅ (n*(n-1))/2
D. ❌ Information given is insufficient
**Correct Answer:** (n*(n-1))/2

---

## Question 18
The worst case occur in quick sort when

### Options:

A. ✅ Pivot is the smallest element
B. ❌ None of the mentioned
C. ❌ Pivot is the median of the array
D. ❌ Pivot is the middle element
**Correct Answer:** Pivot is the smallest element

---

## Question 19
What is the correct output of the below written code?
#include &lt;stdio.h&gt;
void print(int n, int j)
{
if (j &gt;= n)
return;
if (n-j &gt; 0 &amp;&amp; n-j &gt;= j)
printf("%d %d\n", j, n-j);
print(n, j+1);
}
int main()
{
int n = 8;
print(n, 1);
}

### Options:

A. ❌ 1 2<br/>
3 4<br/>
5 6<br/>
7 8
B. ❌ 1 7<br/>
2 6<br/>
3 5<br/>
4 4<br/>
4 4
C. ❌ 1 7<br/>
2 6<br/>
3 5
D. ✅ 1 7<br/>
2 6<br/>
3 5<br/>
4 4
**Correct Answer:** 1 7<br/>
2 6<br/>
3 5<br/>
4 4

---

## Question 20
Suppose there are 11 items in sorted order in an array. How many searches are required on the average, if binary search is employed and all searches are successful in finding the item?

### Options:

A. ❌ 3.33
B. ❌ 2.81
C. ✅ 3.00
D. ❌ 3.46
**Correct Answer:** 3.00

---

## Need Help?

If you're stuck on a question, need clarification, or believe there's an issue with the test, please don't hesitate to reach out!

<a href='mailto:ujjwaljha744@gmail.com?subject=Help%20Needed%20-%20CSE - Mock Test - 03&body=Test%20ID%3A%2064230b63435752f6c4920ccc%0A%0AQuestion%20Number%3A%20%0A%0ADescription%20of%20Issue%3A%20' style='display: inline-block; padding: 10px 20px; background-color: #4CAF50; color: white; text-decoration: none; border-radius: 5px;'>Report Issue / Ask for Help</a>

![Thank You](https://media.giphy.com/media/M9NbzZjAcxq9jS9LZJ/giphy.gif)

*Last updated: 2024-07-22 21:13:06*
