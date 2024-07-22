# 📚 CSE - Practice Test -22

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

## Test Information

- **Test ID:** `642307e243575229728f4bbd`
- **Number of Questions:** `15`
- **Time Limit:** `25 minutes`

---

## Question 1
What does the following function print for n = 25?
void fun(int n)
{
if (n == 0)
return;
printf("%d", n%2);
fun(n/2);
}

### Options:

A. ❌ 11001
B. ✅ 10011
C. ❌ 11111
D. ❌ 00000
**Correct Answer:** 10011

---

## Question 2
Kadane algorithm is used to find:

### Options:

A. ❌ Maximum product subarray in an array
B. ❌ Maximum sum subsequence in an array
C. ❌ Maximum product subsequence in an array
D. ✅ Maximum sum subarray in an array
**Correct Answer:** Maximum sum subarray in an array

---

## Question 3
Consider the polynomial p(x) = a0 + a1x + a2x^2 +a3x^3, where ai != 0, for all i. The minimum number of multiplications needed to evaluate p on an input x is:

### Options:

A. ❌ 9
B. ✅ 3
C. ❌ 6
D. ❌ 4
**Correct Answer:** 3

---

## Question 4
We use dynamic programming approach when

### Options:

A. ✅ The solution has optimal substructure
B. ❌ It’s faster than Greedy
C. ❌ It provides optimal solution
D. ❌ The given problem can be reduced to the 3-SAT problem
**Correct Answer:** The solution has optimal substructure

---

## Question 5
Which of the following standard algorithms is not Dynamic Programming based.

### Options:

A. ❌ 0-1 Knapsack problem
B. ❌ Floyd Warshall Algorithm for all pairs shortest paths
C. ❌ Bellman–Ford Algorithm for single source shortest path
D. ✅ Prim’s Minimum Spanning Tree
**Correct Answer:** Prim’s Minimum Spanning Tree

---

## Question 6
What does fun2() do in general?
int fun(int x, int y)
{
if (y == 0)   return 0;
return (x + fun(x, y-1));
} 
int fun2(int a, int b)
{
if (b == 0) return 1;
return fun(a, fun2(a, b-1));
}

### Options:

A. ❌ x+x*y
B. ❌ y<sup>x</sup>
C. ❌ x*y
D. ✅ x<sup>y</sup>
**Correct Answer:** x<sup>y</sup>

---

## Question 7
Consider a sequence F<sub>00</sub> defined as : F<sub>00</sub>(0) = 1, F<sub>00</sub>(1) = 1 F<sub>00</sub>(n) = 10 <span style='font-family:

"Cambria Math",serif'>∗</span> F<sub>00</sub>(n – 1) + 100 F<sub>00</sub>(n – 2) for n ≥ 2 Then what shall be the set of values of the sequence F<sub>00</sub> ?

### Options:

A. ❌ (1, 110, 600, 1200)
B. ❌ (1, 2, 55, 110, 600, 1200)
C. ❌ (1, 55, 110, 600, 1200)
D. ✅ (1, 110, 1200)
**Correct Answer:** (1, 110, 1200)

---

## Question 8
In dynamic programming, the technique of storing the previously calculated values is called ___________

### Options:

A. ✅ Memoization
B. ❌ Saving value property
C. ❌ Mapping
D. ❌ Storing value property
**Correct Answer:** Memoization

---

## Question 9
If a problem can be broken into subproblems which are reused several times, the problem possesses ____________ property.

### Options:

A. ❌ Greedy
B. ✅ Overlapping subproblems
C. ❌ Memoization
D. ❌ Optimal substructure
**Correct Answer:** Overlapping subproblems

---

## Question 10
When a top-down approach of dynamic programming is applied to a problem, it usually _____________

### Options:

A. ❌ Decreases both, the time complexity and the space complexity
B. ✅ Decreases the time complexity and increases the space complexity
C. ❌ Increases the time complexity and decreases the space complexity
D. ❌ Increases both, the time complexity and the space complexity
**Correct Answer:** Decreases the time complexity and increases the space complexity

---

## Question 11
You are given a knapsack that can carry a maximum weight of 60. There are 4 items with weights {20, 30, 40, 70} and values {70, 80, 90, 200}. What is the maximum value of the items you can carry using the 0-1 knapsack?

### Options:

A. ❌ 200
B. ❌ 90
C. ✅ 160
D. ❌ 170
**Correct Answer:** 160

---

## Question 12
Which of the following standard algorithms is not a Greedy algorithm?

### Options:

A. ❌ Huffman Coding
B. ❌ Dijkstra’s shortest path algorithm
C. ❌ Prim’s algorithm
D. ✅ Bellmen Ford Shortest path algorithm
**Correct Answer:** Bellmen Ford Shortest path algorithm

---

## Question 13
Predict output of following program
#include &lt;stdio.h&gt;
int fun(int n)
{
if (n == 4)
return n;
else return 2*fun(n+1);
}
int main()
{
printf("%d ", fun(2));
return 0;
}

### Options:

A. ❌ Runtime Error
B. ❌ 8
C. ✅ 16
D. ❌ 4
**Correct Answer:** 16

---

## Question 14
We use dynamic programming approach when

### Options:

A. ❌ It provides optimal solution
B. ✅ The solution has optimal substructure
C. ❌ The given problem can be reduced to the 3-SAT problem
D. ❌ It's faster than Greedy
**Correct Answer:** The solution has optimal substructure

---

## Question 15
Consider the following recursive function fun(x, y). What is the value of fun(4, 3)
int fun(int x, int y)
{
if (x == 0)
return y;
return fun(x - 1,  x + y);
}

### Options:

A. ❌ 12
B. ❌ 9
C. ✅ 13
D. ❌ 10
**Correct Answer:** 13

---

## Need Help?

If you're stuck on a question, need clarification, or believe there's an issue with the test, please don't hesitate to reach out!

<a href='mailto:ujjwaljha744@gmail.com?subject=Help%20Needed%20-%20CSE - Practice Test -22&body=Test%20ID%3A%20642307e243575229728f4bbd%0A%0AQuestion%20Number%3A%20%0A%0ADescription%20of%20Issue%3A%20' style='display: inline-block; padding: 10px 20px; background-color: #4CAF50; color: white; text-decoration: none; border-radius: 5px;'>Report Issue / Ask for Help</a>

![Thank You](https://media.giphy.com/media/M9NbzZjAcxq9jS9LZJ/giphy.gif)

*Last updated: 2024-07-22 21:11:19*
