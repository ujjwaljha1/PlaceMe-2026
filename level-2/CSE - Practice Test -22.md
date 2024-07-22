<!-- Markdown content below -->

# 📚 CSE - Practice Test -22 🚀

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

**Test ID:** `642307e243575229728f4bbd` :id:
**Total Questions:** `15` 🧮
**Total Time:** `25 minutes` :hourglass_flowing_sand:

---

## 🔥 Question 1 🧠 🤔

In dynamic programming, the technique of storing the previously calculated values is called ____________

### 📋 Options:
- A. 🟢 Memoization
- B. 🔴 Saving value property
- C. 🔴 Storing value property
- D. 🔴 Mapping

**⭐ Correct Answer:** 🎯 `Memoization`

✨ --- ✨ --- ✨

## 🔥 Question 2 🧠 🤔

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
}_

### 📋 Options:
- A. 🔴 y<sup>x</sup>
- B. 🔴 x*y
- C. 🔴 x+x*y
- D. 🟢 x<sup>y</sup>

**⭐ Correct Answer:** 🎯 `x<sup>y</sup>`

✨ --- ✨ --- ✨

## 🔥 Question 3 🧠 🤔

What does the following function print for n = 25?
void fun(int n)
{
if (n == 0)
return;
printf("%d", n%2);
fun(n/2);
}_

### 📋 Options:
- A. 🔴 11001
- B. 🔴 11111
- C. 🔴 00000
- D. 🟢 10011

**⭐ Correct Answer:** 🎯 `10011`

✨ --- ✨ --- ✨

## 🔥 Question 4 🧠 🤔

We use dynamic programming approach when_

### 📋 Options:
- A. 🔴 The given problem can be reduced to the 3-SAT problem
- B. 🔴 It's faster than Greedy
- C. 🟢 The solution has optimal substructure
- D. 🔴 It provides optimal solution

**⭐ Correct Answer:** 🎯 `The solution has optimal substructure`

✨ --- ✨ --- ✨

## 🔥 Question 5 🧠 🤔

Consider the polynomial p(x) = a0 + a1x + a2x^2 +a3x^3, where ai != 0, for all i. The minimum number of multiplications needed to evaluate p on an input x is:_

### 📋 Options:
- A. 🔴 9
- B. 🔴 6
- C. 🟢 3
- D. 🔴 4

**⭐ Correct Answer:** 🎯 `3`

✨ --- ✨ --- ✨

## 🔥 Question 6 🧠 🤔

Consider the following recursive function fun(x, y). What is the value of fun(4, 3)
int fun(int x, int y)
{
if (x == 0)
return y;
return fun(x - 1,  x + y);
}_

### 📋 Options:
- A. 🟢 13
- B. 🔴 12
- C. 🔴 9
- D. 🔴 10

**⭐ Correct Answer:** 🎯 `13`

✨ --- ✨ --- ✨

## 🔥 Question 7 🧠 🤔

When a top-down approach of dynamic programming is applied to a problem, it usually ______________

### 📋 Options:
- A. 🔴 Decreases both, the time complexity and the space complexity
- B. 🔴 Increases the time complexity and decreases the space complexity
- C. 🔴 Increases both, the time complexity and the space complexity
- D. 🟢 Decreases the time complexity and increases the space complexity

**⭐ Correct Answer:** 🎯 `Decreases the time complexity and increases the space complexity`

✨ --- ✨ --- ✨

## 🔥 Question 8 🧠 🤔

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
}_

### 📋 Options:
- A. 🟢 16
- B. 🔴 4
- C. 🔴 Runtime Error
- D. 🔴 8

**⭐ Correct Answer:** 🎯 `16`

✨ --- ✨ --- ✨

## 🔥 Question 9 🧠 🤔

Kadane algorithm is used to find:_

### 📋 Options:
- A. 🔴 Maximum sum subsequence in an array
- B. 🟢 Maximum sum subarray in an array
- C. 🔴 Maximum product subarray in an array
- D. 🔴 Maximum product subsequence in an array

**⭐ Correct Answer:** 🎯 `Maximum sum subarray in an array`

✨ --- ✨ --- ✨

## 🔥 Question 10 🧠 🤔

Which of the following standard algorithms is not a Greedy algorithm?_

### 📋 Options:
- A. 🟢 Bellmen Ford Shortest path algorithm
- B. 🔴 Dijkstra’s shortest path algorithm
- C. 🔴 Huffman Coding
- D. 🔴 Prim’s algorithm

**⭐ Correct Answer:** 🎯 `Bellmen Ford Shortest path algorithm`

✨ --- ✨ --- ✨

## 🔥 Question 11 🧠 🤔

If a problem can be broken into subproblems which are reused several times, the problem possesses ____________ property._

### 📋 Options:
- A. 🟢 Overlapping subproblems
- B. 🔴 Optimal substructure
- C. 🔴 Greedy
- D. 🔴 Memoization

**⭐ Correct Answer:** 🎯 `Overlapping subproblems`

✨ --- ✨ --- ✨

## 🔥 Question 12 🧠 🤔

We use dynamic programming approach when_

### 📋 Options:
- A. 🟢 The solution has optimal substructure
- B. 🔴 It’s faster than Greedy
- C. 🔴 It provides optimal solution
- D. 🔴 The given problem can be reduced to the 3-SAT problem

**⭐ Correct Answer:** 🎯 `The solution has optimal substructure`

✨ --- ✨ --- ✨

## 🔥 Question 13 🧠 🤔

Consider a sequence F<sub>00</sub> defined as : F<sub>00</sub>(0) = 1, F<sub>00</sub>(1) = 1 F<sub>00</sub>(n) = 10 <span style='font-family:

"Cambria Math",serif'>∗</span> F<sub>00</sub>(n – 1) + 100 F<sub>00</sub>(n – 2) for n ≥ 2 Then what shall be the set of values of the sequence F<sub>00</sub> ?_

### 📋 Options:
- A. 🟢 (1, 110, 1200)
- B. 🔴 (1, 110, 600, 1200)
- C. 🔴 (1, 2, 55, 110, 600, 1200)
- D. 🔴 (1, 55, 110, 600, 1200)

**⭐ Correct Answer:** 🎯 `(1, 110, 1200)`

✨ --- ✨ --- ✨

## 🔥 Question 14 🧠 🤔

Which of the following standard algorithms is not Dynamic Programming based._

### 📋 Options:
- A. 🔴 0-1 Knapsack problem
- B. 🟢 Prim’s Minimum Spanning Tree
- C. 🔴 Floyd Warshall Algorithm for all pairs shortest paths
- D. 🔴 Bellman–Ford Algorithm for single source shortest path

**⭐ Correct Answer:** 🎯 `Prim’s Minimum Spanning Tree`

✨ --- ✨ --- ✨

## 🔥 Question 15 🧠 🤔

You are given a knapsack that can carry a maximum weight of 60. There are 4 items with weights {20, 30, 40, 70} and values {70, 80, 90, 200}. What is the maximum value of the items you can carry using the 0-1 knapsack?_

### 📋 Options:
- A. 🔴 200
- B. 🔴 170
- C. 🟢 160
- D. 🔴 90

**⭐ Correct Answer:** 🎯 `160`

✨ --- ✨ --- ✨

## :sos: Need Help? ✋

💬 If you encounter any issues or have questions, please don't hesitate to reach out!

🔗 [Report an Issue](https://example.com/report-issue)

![Thank You](https://media.giphy.com/media/3o6Zt6KHxJTbXCnSvu/giphy.gif)

:clock10: *Last updated: 2024-07-22 18:07:05*
