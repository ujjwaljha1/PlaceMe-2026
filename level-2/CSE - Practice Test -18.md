<!-- Markdown content below -->

# 📚 CSE - Practice Test -18 🚀

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

**Test ID:** `642307b743575277328f270e` :id:
**Total Questions:** `15` 🧮
**Total Time:** `25 minutes` :hourglass_flowing_sand:

---

## 🔥 Question 1 🧠 🤔

Consider the following C program
int main()
{
int x, y, m, n;
scanf ("%d %d", &amp;x, &amp;y);
/* x &gt; 0 and y &gt; 0 */
m = x; n = y;
while (m != n)
{
if(m&gt;n)
m = m - n;
else
n = n - m;
}
printf("%d", n);
}
What does the program compute?_

### 📋 Options:
- A. 🔴 x mod y using repeated subtraction
- B. 🔴 the least common multiple of x and y
- C. 🔴 x + y using repeated subtraction
- D. 🟢 the greatest common divisor of x and y

**⭐ Correct Answer:** 🎯 `the greatest common divisor of x and y`

✨ --- ✨ --- ✨

## 🔥 Question 2 🧠 🤔

What does it mean when we say that an algorithm X is asymptotically more efficient than Y?_

### 📋 Options:
- A. 🔴 X will be a better choice for all inputs except large inputs
- B. 🟢 X will be a better choice for all inputs except small inputs
- C. 🔴 X will be a better choice for all inputs
- D. 🔴 Y will be a better choice for small inputs

**⭐ Correct Answer:** 🎯 `X will be a better choice for all inputs except small inputs`

✨ --- ✨ --- ✨

## 🔥 Question 3 🧠 🤔

What is the time complexity of the below function?
void fun(int n, int arr[])
{
int i = 0, j = 0;
for(; i &lt; n; ++i)
while(j &lt; n &amp;&amp; arr[i] &lt; arr[j])
j++;
}_

### 📋 Options:
- A. 🔴 O(n^2)
- B. 🔴 O(n(logn)^2)
- C. 🔴 O(nlogn)
- D. 🟢 O(n)

**⭐ Correct Answer:** 🎯 `O(n)`

✨ --- ✨ --- ✨

## 🔥 Question 4 🧠 🤔

Which of the following is correct recurrence for worst case of Binary Search?_

### 📋 Options:
- A. 🔴 T(n) = T(n-1) + O(1) and T(1) = T(0) = O(1)
- B. 🔴 T(n) = 2T(n/2) + O(1) and T(1) = T(0) = O(1)
- C. 🟢 T(n) = T(n/2) + O(1) and T(1) = T(0) = O(1)
- D. 🔴 T(n) = T(n-2) + O(1) and T(1) = T(0) = O(1

**⭐ Correct Answer:** 🎯 `T(n) = T(n/2) + O(1) and T(1) = T(0) = O(1)`

✨ --- ✨ --- ✨

## 🔥 Question 5 🧠 🤔

Step(s) in Divide and conquer process that takes a recursive approach is said to be_

### 📋 Options:
- A. 🟢 Divide/Break
- B. 🔴 Conquer/Solve
- C. 🔴 Both B and C
- D. 🔴 Merge/Combine

**⭐ Correct Answer:** 🎯 `Divide/Break`

✨ --- ✨ --- ✨

## 🔥 Question 6 🧠 🤔

The complexity of Fibonacci series is_

### 📋 Options:
- A. 🔴 O(n log n)
- B. 🔴 O(n2)
- C. 🔴 O(log n)
- D. 🟢 O(2n)

**⭐ Correct Answer:** 🎯 `O(2n)`

✨ --- ✨ --- ✨

## 🔥 Question 7 🧠 🤔

The given array is arr = {2,6,1}. What are the pivots that are returned as a result of subsequent partitioning?_

### 📋 Options:
- A. 🔴 2 and 6
- B. 🔴 1 and 6
- C. 🔴 6 and 1
- D. 🟢 None of the mentioned

**⭐ Correct Answer:** 🎯 `None of the mentioned`

✨ --- ✨ --- ✨

## 🔥 Question 8 🧠 🤔

QuickSort can be categorized into which of the following?_

### 📋 Options:
- A. 🔴 Dynamic programming
- B. 🟢 Divide and conquer
- C. 🔴 Greedy algorithm
- D. 🔴 Brute Force technique

**⭐ Correct Answer:** 🎯 `Divide and conquer`

✨ --- ✨ --- ✨

## 🔥 Question 9 🧠 🤔

An algorithm is a _________ set of precise instructions for performing computation._

### 📋 Options:
- A. 🟢 Finite
- B. 🔴 Infinite
- C. 🔴 Constant
- D. 🔴 None of the mentioned

**⭐ Correct Answer:** 🎯 `Finite`

✨ --- ✨ --- ✨

## 🔥 Question 10 🧠 🤔

The minimum number of comparisons required to find the minimum and the maximum of 100 numbers is ______________._

### 📋 Options:
- A. 🔴 140
- B. 🟢 148
- C. 🔴 147
- D. 🔴 146

**⭐ Correct Answer:** 🎯 `148`

✨ --- ✨ --- ✨

## 🔥 Question 11 🧠 🤔

What is the value of following recurrence?
T(n) = T(n/4) + T(n/2) + cn^2
T(1) = c
T(0) = 0
Where c is a positive constant_

### 📋 Options:
- A. 🔴 O(nLogn)
- B. 🟢 O(n^2)
- C. 🔴 O(n^2 Logn)
- D. 🔴 O(n^3)

**⭐ Correct Answer:** 🎯 `O(n^2)`

✨ --- ✨ --- ✨

## 🔥 Question 12 🧠 🤔

Consider a sorted array of n numbers. What would be the time complexity of the best known algorithm to find a pair a and b such that |a-b| = k , k being a positive integer._

### 📋 Options:
- A. 🔴 O(logn)
- B. 🔴 O(nlog n)
- C. 🔴 O(n2)
- D. 🟢 O(n)

**⭐ Correct Answer:** 🎯 `O(n)`

✨ --- ✨ --- ✨

## 🔥 Question 13 🧠 🤔

The time complexity of the following C function is (assume n &gt; 0
int recursive (int n)
{
if (n == 1)
return (1);
else
return (recursive (n-1) + recursive (n-1));
}_

### 📋 Options:
- A. 🟢 0(2^n)
- B. 🔴 0(nlogn)
- C. 🔴 0(n^2)
- D. 🔴 0(n)

**⭐ Correct Answer:** 🎯 `0(2^n)`

✨ --- ✨ --- ✨

## 🔥 Question 14 🧠 🤔

Which of the following is TRUE?_

### 📋 Options:
- A. 🔴 The cost of searching an AVL tree is θ (log n) but that of a complete binary tree is θ (n log n)
- B. 🔴 The cost of searching an AVL tree is θ (n log n) but that of a binary search tree is O(n)
- C. 🔴 The cost of searching a binary search tree is O (log n ) but that of an AVL tree is θ(n)
- D. 🟢 The cost of searching an AVL tree is θ (log n) but that of a binary search tree is O(n)

**⭐ Correct Answer:** 🎯 `The cost of searching an AVL tree is θ (log n) but that of a binary search tree is O(n)`

✨ --- ✨ --- ✨

## 🔥 Question 15 🧠 🤔

The auxiliary space of insertion sort is O(1), what does O(1) mean ?_

### 📋 Options:
- A. 🟢 It means the amount of extra memory Insertion Sort consumes doesn’t depend on the input. The algorithm should use the same amount of memory for all inputs.
- B. 🔴 The memory (space) required to process the data is not constant.
- C. 🔴 It takes only 1 kb of memory.
- D. 🔴 It is the speed at which the elements are traversed.

**⭐ Correct Answer:** 🎯 `It means the amount of extra memory Insertion Sort consumes doesn’t depend on the input. The algorithm should use the same amount of memory for all inputs.`

✨ --- ✨ --- ✨

## :sos: Need Help? ✋

💬 If you encounter any issues or have questions, please don't hesitate to reach out!

🔗 [Report an Issue](https://example.com/report-issue)

![Thank You](https://media.giphy.com/media/3o6Zt6KHxJTbXCnSvu/giphy.gif)

:clock10: *Last updated: 2024-07-22 18:05:13*
