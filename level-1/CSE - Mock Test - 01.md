# 📚 CSE - Mock Test - 01

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

## Test Information

- **Test ID:** `64230b4e4357527a7891ff26`
- **Number of Questions:** `20`
- **Time Limit:** `35 minutes`

---

## Question 1
Let A[1…n] be an array of n distinct numbers. If i &lt; j and A[i] &gt; A[j], then the pair (i, j) is called an inversion of A. What is the expected number of inversions in any permutation on n elements?

### Options:

A. ❌ <!-- MathType@Translator@5@5@MathML2 (DataObject).tdl@MathML 2.0 (DataObject)@ --><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>θ</mi></math><!-- MathType@End@5@5@ -->(n)
B. ✅ <!-- MathType@Translator@5@5@MathML2 (DataObject).tdl@MathML 2.0 (DataObject)@ --><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>θ</mi></math><!-- MathType@End@5@5@ -->(n^2)
C. ❌ <!-- MathType@Translator@5@5@MathML2 (DataObject).tdl@MathML 2.0 (DataObject)@ --><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>θ</mi></math><!-- MathType@End@5@5@ -->(logn)
D. ❌ <!-- MathType@Translator@5@5@MathML2 (DataObject).tdl@MathML 2.0 (DataObject)@ --><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>θ</mi></math><!-- MathType@End@5@5@ -->(nlgon)
**Correct Answer:** <!-- MathType@Translator@5@5@MathML2 (DataObject).tdl@MathML 2.0 (DataObject)@ --><math xmlns="http://www.w3.org/1998/Math/MathML"><mi>θ</mi></math><!-- MathType@End@5@5@ -->(n^2)

---

## Question 2
Which of the below Figure is following AVL Tree property
<img alt="" src="https://hub.myperfectice.com/uploads/image/58dde32f02806f00011effc4/bxh8yf/upload-1531034186662.png" style="width: 245px; height: 113px;"/>

### Options:

A. ❌ Only I
B. ❌ None of the above
C. ✅ Both I &amp; II
D. ❌ Only II
**Correct Answer:** Both I &amp; II

---

## Question 3
<p style="text-align:justify;text-justify:inter-ideograph">void fun(int n)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">Stack S; 
<p style="text-align:justify;text-justify:inter-ideograph">while (n &gt; 0)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">push(&amp;S, n%2);
<p style="text-align:justify;text-justify:inter-ideograph">n = n/2;
<p style="text-align:justify;text-justify:inter-ideograph">}
<p style="text-align:justify;text-justify:inter-ideograph">while (!isEmpty(&amp;S))
<p style="text-align:justify;text-justify:inter-ideograph">printf("%d ", pop(&amp;S));
<p style="text-align:justify;text-justify:inter-ideograph">}
What does the above function do?

### Options:

A. ❌ Prints the value of Logn in reverse order
B. ❌ Prints binary representation of n in reverse order
C. ✅ Prints binary representation of n
D. ❌ Prints the value of Logn
**Correct Answer:** Prints binary representation of n

---

## Question 4
What are the disadvantages of arrays?

### Options:

A. ✅ All of the mentioned
B. ❌ There are chances of wastage of memory space if elements inserted in an array are lesser than than the allocated size
C. ❌ We must know before hand how many elements will be there in the array
D. ❌ Insertion and deletion becomes tedious
**Correct Answer:** All of the mentioned

---

## Question 5
Which of the following operations is not O(1) for an array of sorted data. You may assume that array elements are distinct?

### Options:

A. ❌ Find the ith largest element
B. ❌ Find the ith smallest element
C. ✅ Delete an element
D. ❌ All of the above
**Correct Answer:** Delete an element

---

## Question 6
The number of edges from the root to the node is called _____ of the tree.

### Options:

A. ❌ None of the above
B. ✅ Height
C. ❌ Length
D. ❌ Depth
**Correct Answer:** Height

---

## Question 7
Which of the following is a key factor for preferring B<sup>+</sup> trees to BST for indexing db relation?

### Options:

A. ❌ DB relation are sorted on the primary key
B. ✅ Data transfer from hard disk is in Blocks
C. ❌ DB relation has a large number of records
D. ❌ B<sup>+</sup> trees require keys memory than BST
**Correct Answer:** Data transfer from hard disk is in Blocks

---

## Question 8
Maximum height of a balanced Binary Search tree with n keys

### Options:

A. ✅ O(log n)
B. ❌ O(n<sup>2</sup>)
C. ❌ O(n log n)
D. ❌ O(n)
**Correct Answer:** O(log n)

---

## Question 9
What does ‘stack underflow’ refer to?

### Options:

A. ❌ index out of bounds exception
B. ❌ adding items to a full stack
C. ❌ accessing item from an undefined stack
D. ✅ removing items from an empty stack
**Correct Answer:** removing items from an empty stack

---

## Question 10
Special node in tree structure which has many children and no parent node is called.

### Options:

A. ✅ Root node
B. ❌ Leaf node
C. ❌ Search node
D. ❌ Descendant nodes
**Correct Answer:** Root node

---

## Question 11
What is an AVL Tree?

### Options:

A. ❌ A tree with 3 children
B. ❌ A tree which unbalanced &amp; is a height balance tree.
C. ✅ A balance tree
D. ❌ A tree at most 3 children
**Correct Answer:** A balance tree

---

## Question 12
A single array A[1..MAXSIZE] is used to implement two stacks. The two stacks grow from opposite ends of the array. Variables top1 and top2 (topl&lt; top 2) point to the location of the topmost element in each of the stacks. If the space is to be used efficiently, the condition for “stack full” is

### Options:

A. ✅ top1= top2 -1
B. ❌ (top1= MAXSIZE/2) or (top2 = MAXSIZE)
C. ❌ (top1 = MAXSIZE/2) and (top2 = MAXSIZE/2+1)
D. ❌ top1 + top2 = MAXSIZE
**Correct Answer:** top1= top2 -1

---

## Question 13
<p style="text-align:justify;text-justify:inter-ideograph">Consider the following pseudo code. Assume that IntQueue is an integer queue. What does the function fun do?
<p style="text-align:justify;text-justify:inter-ideograph">void fun(int n)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">IntQueue q = new IntQueue();
<p style="text-align:justify;text-justify:inter-ideograph">q.enqueue(0);
<p style="text-align:justify;text-justify:inter-ideograph">q.enqueue(1);
<p style="text-align:justify;text-justify:inter-ideograph">for (int i = 0; i &lt; n; i++)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">int a = q.dequeue();
<p style="text-align:justify;text-justify:inter-ideograph">int b = q.dequeue();
<p style="text-align:justify;text-justify:inter-ideograph">q.enqueue(b);
<p style="text-align:justify;text-justify:inter-ideograph">q.enqueue(a + b);
<p style="text-align:justify;text-justify:inter-ideograph">ptint(a);
<p style="text-align:justify;text-justify:inter-ideograph">}
}

### Options:

A. ❌ Prints numbers from 0 to n-1
B. ❌ Prints numbers from n-1 to 0
C. ❌ Prints first n Fibonacci numbers in reverse order
D. ✅ Prints first n Fibonacci numbers
**Correct Answer:** Prints first n Fibonacci numbers

---

## Question 14
Consider a B<sup>+</sup> tree in which the maximum number of keys in a node is 5. What is the minimum number of keys in any non-root node?

### Options:

A. ❌ 1
B. ❌ 3
C. ✅ 2
D. ❌ 4
**Correct Answer:** 2

---

## Question 15
<p style="text-align:justify;text-justify:inter-ideograph">Consider the following pseudocode that uses a stack
<p style="text-align:justify;text-justify:inter-ideograph">declare a stack of characters
<p style="text-align:justify;text-justify:inter-ideograph">while ( there are more characters in the word to read )
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">read a character
<p style="text-align:justify;text-justify:inter-ideograph">push the character on the stack
<p style="text-align:justify;text-justify:inter-ideograph">}
<p style="text-align:justify;text-justify:inter-ideograph">while ( the stack is not empty )
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">pop a character off the stack
<p style="text-align:justify;text-justify:inter-ideograph">write the character to the screen
<p style="text-align:justify;text-justify:inter-ideograph">}
What is output for input “XYZ”?

### Options:

A. ❌ XYZ
B. ❌ ZYXZYX
C. ✅ ZYX
D. ❌ XYZXYZ
**Correct Answer:** ZYX

---

## Question 16
What is a full Binary tree?

### Options:

A. ❌ Each mode has exactly zero or two children
B. ❌ Each mode has exactly two children
C. ❌ Each mode has exactly one or two children
D. ✅ All the leaves are at the same level.
**Correct Answer:** All the leaves are at the same level.

---

## Question 17
Non leaf nodes of tree structure form a

### Options:

A. ❌ All of these
B. ❌ Sparse Indices
C. ✅ Multilevel dense indices
D. ❌ Multilevel clustered Indices
**Correct Answer:** Multilevel dense indices

---

## Question 18
<p style="text-align:justify;text-justify:inter-ideograph">The following function reverse() is supposed to reverse a singly linked list. There is one line missing at the end of the function.
<p style="text-align:justify;text-justify:inter-ideograph">struct node
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">int data;
<p style="text-align:justify;text-justify:inter-ideograph">struct node* next;
<p style="text-align:justify;text-justify:inter-ideograph">};
<p style="text-align:justify;text-justify:inter-ideograph">static void reverse(struct node** head_ref)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">struct node* pre   = NULL;
<p style="text-align:justify;text-justify:inter-ideograph">struct node* curr = *head_ref;
<p style="text-align:justify;text-justify:inter-ideograph">struct node* next;
<p style="text-align:justify;text-justify:inter-ideograph">while (current != NULL)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">next  = curr-&gt;next; 
<p style="text-align:justify;text-justify:inter-ideograph">curr-&gt;next = prev;  
<p style="text-align:justify;text-justify:inter-ideograph">prev = current;
<p style="text-align:justify;text-justify:inter-ideograph">current = next;
<p style="text-align:justify;text-justify:inter-ideograph">}
<p style="text-align:justify;text-justify:inter-ideograph">/*ADD A STATEMENT HERE*/
<p style="text-align:justify;text-justify:inter-ideograph">}
What should be added in place of “/*ADD A STATEMENT HERE*/”, so that the function correctly reverses a linked list.

### Options:

A. ❌ *head_ref = NULL;
B. ❌ *head_ref = next;
C. ❌ *head_ref = current;
D. ✅ *head_ref = prev;
**Correct Answer:** *head_ref = prev;

---

## Question 19
Which of the following applications may use a stack?

### Options:

A. ❌ A parentheses balancing program.
B. ✅ All of the mentioned.
C. ❌ Tracking of local variables at run time.
D. ❌ Compiler Syntax Analyzer.
**Correct Answer:** All of the mentioned.

---

## Question 20
Which algorithm is used to compute minimum spanning tree

### Options:

A. ❌ DFS
B. ❌ Both (A) &amp; (B)
C. ❌ BFS
D. ✅ Kruskal’s
**Correct Answer:** Kruskal’s

---

## Need Help?

If you're stuck on a question, need clarification, or believe there's an issue with the test, please don't hesitate to reach out!

<a href='mailto:ujjwaljha744@gmail.com?subject=Help%20Needed%20-%20CSE - Mock Test - 01&body=Test%20ID%3A%2064230b4e4357527a7891ff26%0A%0AQuestion%20Number%3A%20%0A%0ADescription%20of%20Issue%3A%20' style='display: inline-block; padding: 10px 20px; background-color: #4CAF50; color: white; text-decoration: none; border-radius: 5px;'>Report Issue / Ask for Help</a>

![Thank You](https://media.giphy.com/media/M9NbzZjAcxq9jS9LZJ/giphy.gif)

*Last updated: 2024-07-22 20:54:06*
