# 📚 CSE - Practice Test -18

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

## Test Information

- **Test ID:** `642307b743575277328f270e`
- **Number of Questions:** `15`
- **Time Limit:** `25 minutes`

---

## Question 1
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
What does the program compute?

### Options:

A. ❌ x mod y using repeated subtraction
B. ✅ the greatest common divisor of x and y
C. ❌ x + y using repeated subtraction
D. ❌ the least common multiple of x and y
**Correct Answer:** the greatest common divisor of x and y

---

## Question 2
The auxiliary space of insertion sort is O(1), what does O(1) mean ?

### Options:

A. ❌ The memory (space) required to process the data is not constant.
B. ❌ It is the speed at which the elements are traversed.
C. ✅ It means the amount of extra memory Insertion Sort consumes doesn’t depend on the input. The algorithm should use the same amount of memory for all inputs.
D. ❌ It takes only 1 kb of memory.
**Correct Answer:** It means the amount of extra memory Insertion Sort consumes doesn’t depend on the input. The algorithm should use the same amount of memory for all inputs.

---

## Question 3
An algorithm is a _________ set of precise instructions for performing computation.

### Options:

A. ❌ Constant
B. ✅ Finite
C. ❌ Infinite
D. ❌ None of the mentioned
**Correct Answer:** Finite

---

## Question 4
The complexity of Fibonacci series is

### Options:

A. ❌ O(n log n)
B. ✅ O(2n)
C. ❌ O(n2)
D. ❌ O(log n)
**Correct Answer:** O(2n)

---

## Question 5
The time complexity of the following C function is (assume n &gt; 0
int recursive (int n)
{
if (n == 1)
return (1);
else
return (recursive (n-1) + recursive (n-1));
}

### Options:

A. ❌ 0(n^2)
B. ❌ 0(nlogn)
C. ❌ 0(n)
D. ✅ 0(2^n)
**Correct Answer:** 0(2^n)

---

## Question 6
The given array is arr = {2,6,1}. What are the pivots that are returned as a result of subsequent partitioning?

### Options:

A. ❌ 6 and 1
B. ❌ 1 and 6
C. ❌ 2 and 6
D. ✅ None of the mentioned
**Correct Answer:** None of the mentioned

---

## Question 7
Which of the following is correct recurrence for worst case of Binary Search?

### Options:

A. ❌ T(n) = 2T(n/2) + O(1) and T(1) = T(0) = O(1)
B. ❌ T(n) = T(n-1) + O(1) and T(1) = T(0) = O(1)
C. ✅ T(n) = T(n/2) + O(1) and T(1) = T(0) = O(1)
D. ❌ T(n) = T(n-2) + O(1) and T(1) = T(0) = O(1
**Correct Answer:** T(n) = T(n/2) + O(1) and T(1) = T(0) = O(1)

---

## Question 8
The minimum number of comparisons required to find the minimum and the maximum of 100 numbers is ______________.

### Options:

A. ❌ 147
B. ❌ 146
C. ❌ 140
D. ✅ 148
**Correct Answer:** 148

---

## Question 9
Step(s) in Divide and conquer process that takes a recursive approach is said to be

### Options:

A. ✅ Divide/Break
B. ❌ Both B and C
C. ❌ Merge/Combine
D. ❌ Conquer/Solve
**Correct Answer:** Divide/Break

---

## Question 10
What is the value of following recurrence?
T(n) = T(n/4) + T(n/2) + cn^2
T(1) = c
T(0) = 0
Where c is a positive constant

### Options:

A. ❌ O(n^2 Logn)
B. ❌ O(n^3)
C. ✅ O(n^2)
D. ❌ O(nLogn)
**Correct Answer:** O(n^2)

---

## Question 11
What is the time complexity of the below function?
void fun(int n, int arr[])
{
int i = 0, j = 0;
for(; i &lt; n; ++i)
while(j &lt; n &amp;&amp; arr[i] &lt; arr[j])
j++;
}

### Options:

A. ❌ O(n^2)
B. ❌ O(n(logn)^2)
C. ✅ O(n)
D. ❌ O(nlogn)
**Correct Answer:** O(n)

---

## Question 12
QuickSort can be categorized into which of the following?

### Options:

A. ❌ Greedy algorithm
B. ✅ Divide and conquer
C. ❌ Brute Force technique
D. ❌ Dynamic programming
**Correct Answer:** Divide and conquer

---

## Question 13
Consider a sorted array of n numbers. What would be the time complexity of the best known algorithm to find a pair a and b such that |a-b| = k , k being a positive integer.

### Options:

A. ❌ O(n2)
B. ❌ O(logn)
C. ❌ O(nlog n)
D. ✅ O(n)
**Correct Answer:** O(n)

---

## Question 14
What does it mean when we say that an algorithm X is asymptotically more efficient than Y?

### Options:

A. ❌ Y will be a better choice for small inputs
B. ❌ X will be a better choice for all inputs
C. ✅ X will be a better choice for all inputs except small inputs
D. ❌ X will be a better choice for all inputs except large inputs
**Correct Answer:** X will be a better choice for all inputs except small inputs

---

## Question 15
Which of the following is TRUE?

### Options:

A. ❌ The cost of searching a binary search tree is O (log n ) but that of an AVL tree is θ(n)
B. ❌ The cost of searching an AVL tree is θ (n log n) but that of a binary search tree is O(n)
C. ✅ The cost of searching an AVL tree is θ (log n) but that of a binary search tree is O(n)
D. ❌ The cost of searching an AVL tree is θ (log n) but that of a complete binary tree is θ (n log n)
**Correct Answer:** The cost of searching an AVL tree is θ (log n) but that of a binary search tree is O(n)

---

## Need Help?

If you're stuck on a question, need clarification, or believe there's an issue with the test, please don't hesitate to reach out!

<a href='mailto:ujjwaljha744@gmail.com?subject=Help%20Needed%20-%20CSE - Practice Test -18&body=Test%20ID%3A%20642307b743575277328f270e%0A%0AQuestion%20Number%3A%20%0A%0ADescription%20of%20Issue%3A%20' style='display: inline-block; padding: 10px 20px; background-color: #4CAF50; color: white; text-decoration: none; border-radius: 5px;'>Report Issue / Ask for Help</a>

![Thank You](https://media.giphy.com/media/M9NbzZjAcxq9jS9LZJ/giphy.gif)

*Last updated: 2024-07-22 21:04:33*
