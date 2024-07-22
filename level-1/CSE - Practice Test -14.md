# 📚 CSE - Practice Test -14

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

## Test Information

- **Test ID:** `6423077e435752649a8efed9`
- **Number of Questions:** `15`
- **Time Limit:** `25 minutes`

---

## Question 1
If the element “A”, “B”. “C”, &amp; “D” are Placed in a queue and are deleted one at a time, in what order they will be removed?

### Options:

A. ❌ DCBA
B. ❌ CBAD
C. ❌ DCAB
D. ✅ ABCD
**Correct Answer:** ABCD

---

## Question 2
Which of the following is not an application of Priority QUEUE?

### Options:

A. ❌ Dijkastra’s single source shortest Path Algorithm.
B. ✅ BFS algorithm
C. ❌ Prim’s Algorithm
D. ❌ Huffman codes
**Correct Answer:** BFS algorithm

---

## Question 3
A normal QUEUE, if implemented using an array of size MAX-SIZE, gets full when

### Options:

A. ✅ Rear = MAX-SIZE – 1
B. ❌ Front = (rear + 1)% MAX-SIZE
C. ❌ Rear = Front
D. ❌ Front = rear + 1;
**Correct Answer:** Rear = MAX-SIZE – 1

---

## Question 4
What are the time complexities of finding 8th element from beginning and 8th element from end in a singly linked list?
Let n be the number of nodes in linked list, you may assume that n &gt; 8.

### Options:

A. ❌ O(1) and O(1)
B. ✅ O(1) and O(n)
C. ❌ O(n) and O(n)
D. ❌ O(n) and O(1)
**Correct Answer:** O(1) and O(n)

---

## Question 5
Which of the following sorting algorithms can be used to sort a random linked list with minimum time complexity?

### Options:

A. ❌ Quick Sort
B. ❌ Insertion Sort
C. ❌ Heap Sort
D. ✅ Merge Sort
**Correct Answer:** Merge Sort

---

## Question 6
Which of the following is true about linked list implementation of queue?

### Options:

A. ❌ In push operation, if new nodes are inserted at the end, then in pop operation, nodes must be removed from the beginning
B. ✅ Both a and b
C. ❌ None of the mentioned
D. ❌ In push operation, if new nodes are inserted at the beginning of linked list, then in pop operation, nodes must be removed from end
**Correct Answer:** Both a and b

---

## Question 7
<p style="text-align:justify;text-justify:inter-ideograph">void fun(Queue *Q)
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">Stack S;  // Say it creates an empty stack S
<p style="text-align:justify;text-justify:inter-ideograph">// Run while Q is not empty
<p style="text-align:justify;text-justify:inter-ideograph">while (!isEmpty(Q))
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">// deQueue an item from Q and push the dequeued item to S
<p style="text-align:justify;text-justify:inter-ideograph">push(&amp;S, deQueue(Q));
<p style="text-align:justify;text-justify:inter-ideograph">}
<p style="text-align:justify;text-justify:inter-ideograph">// Run while Stack S is not empty
<p style="text-align:justify;text-justify:inter-ideograph">while (!isEmpty(&amp;S))
<p style="text-align:justify;text-justify:inter-ideograph">{
<p style="text-align:justify;text-justify:inter-ideograph">// Pop an item from S and enqueue the poppped item to Q
<p style="text-align:justify;text-justify:inter-ideograph">enQueue(Q, pop(&amp;S));
<p style="text-align:justify;text-justify:inter-ideograph">}
<p style="text-align:justify;text-justify:inter-ideograph">}
<p style="text-align:justify;text-justify:inter-ideograph">Above function takes a Queue as an argument and uses a stack S to do processing.
What does the above function do in general?

### Options:

A. ❌ Removes the last from Q
B. ❌ Keeps the Q same as it was before the call
C. ✅ Reverses the Q
D. ❌ Makes Q empty
**Correct Answer:** Reverses the Q

---

## Question 8
What is the output of following function for start pointing to first node of following linked list?
1-&gt;2-&gt;3-&gt;4-&gt;5-&gt;6
void fun(struct node* start)
{
  if(start == NULL)
    return;
  printf("%d  ", start-&gt;data);
 
  if(start-&gt;next != NULL )
    fun(start-&gt;next-&gt;next);
  printf("%d  ", start-&gt;data);
}

### Options:

A. ✅ 1 3 5 5 3 1
B. ❌ 1 2 3 5
C. ❌ 1 4 6 6 4 1
D. ❌ 1 3 5 1 3 5
**Correct Answer:** 1 3 5 5 3 1

---

## Question 9
Which of the following can be the base case for the recursive implementation used to find the length of linked list?

### Options:

A. ❌ if(current_node-&gt;next == 0) return 0
B. ✅ if(current_node == 0) return 0
C. ❌ if(current_node-&gt;next == 0) return 1
D. ❌ if(current_node == 0) return 1
**Correct Answer:** if(current_node == 0) return 0

---

## Question 10
What is the time complexity of the following iterative implementation used to find the length of a linked list?
#include&lt;stdio.h&gt;<br/>
#include&lt;stdlib.h&gt;<br/>
struct Node<br/>
{<br/>
      int val;<br/>
      struct Node *next;<br/>
}*head;<br/>
int get_len()<br/>
{<br/>
      struct Node *temp = head-&gt;next;<br/>
      int len = 0;<br/>
      while(temp != 0)<br/>
      {<br/>
          len++;<br/>
          temp = temp-&gt;next;<br/>
      }<br/>
      return len;<br/>
}<br/>
int main()<br/>
{<br/>
      int arr[10] = {1,2,3,4,5}, n = 5, i;<br/>
      struct Node *temp, *newNode;<br/>
      head = (struct Node*)malloc(sizeof(struct Node));<br/>
      head-&gt;next = 0;<br/>
      temp = head;<br/>
      for(i=0; i&lt;n; i++)<br/>
      {<br/>
          newNode = (struct Node*)malloc(sizeof(struct Node));<br/>
          newNode-&gt;val = arr[i];<br/>
          newNode-&gt;next = 0;<br/>
          temp-&gt;next = newNode;<br/>
          temp = temp-&gt;next;<br/>
      }<br/>
      int len = get_len();<br/>
      printf("%d",len);<br/>
      return 0;<br/>
}

### Options:

A. ❌ O(logn)
B. ❌ O(n<sup>2</sup>)
C. ❌ O(1)
D. ✅ O(n)
**Correct Answer:** O(n)

---

## Question 11
The following C function takes a single-linked list of integers as a parameter and rearranges the elements of the list. The function is called with the list containing the integers 1, 2, 3, 4, 5, 6, 7 in the given order. What will be the contents of the list after the function completes execution?
struct node
{
  int value;
  struct node *next;
};
void rearrange(struct node *list)
{
  struct node *p, * q;
  int temp;
  if ((!list) || !list-&gt;next)
      return;
  p = list;
  q = list-&gt;next;
  while(q)
  {
     temp = p-&gt;value;
     p-&gt;value = q-&gt;value;
     q-&gt;value = temp;
     p = q-&gt;next;
     q = p?p-&gt;next:0;
  }
}

### Options:

A. ❌ 2,3,4,5,6,7,1
B. ❌ 1,3,2,5,4,7,6
C. ❌ 1,2,3,4,5,6,7
D. ✅ 2,1,4,3,6,5,7
**Correct Answer:** 2,1,4,3,6,5,7

---

## Question 12
<p style="text-align:justify;text-justify:inter-ideograph">Consider the following statements:
<p style="text-align:justify;text-justify:inter-ideograph">i.   First-in-first out types of computations are efficiently supported by STACKS.
<p style="text-align:justify;text-justify:inter-ideograph">ii.  Implementing LISTS on linked lists is more efficient than implementing LISTS on
<p style="text-align:justify;text-justify:inter-ideograph">     an array for almost all the basic LIST operations.
<p style="text-align:justify;text-justify:inter-ideograph">iii. Implementing QUEUES on a circular array is more efficient than implementing QUEUES
<p style="text-align:justify;text-justify:inter-ideograph">     on a linear array with two indices.
<p style="text-align:justify;text-justify:inter-ideograph">iv.  Last-in-first-out type of computations are efficiently supported by QUEUES.
Which of the following is correct?

### Options:

A. ✅ (ii) and (iii) are true
B. ❌ (ii) and (iv) are true
C. ❌ (iii) and (iv) are true
D. ❌ (i) and (ii) are true
**Correct Answer:** (ii) and (iii) are true

---

## Question 13
What does the following Piece of code do?
Public object function ()
{
If (isEmphy ())
return –999;
else
{
Object high;
high = Queue[front]
return high;
{
{

### Options:

A. ❌ None of the above
B. ❌ Dequeue
C. ✅ Return of the Front element
D. ❌ Enqueue
**Correct Answer:** Return of the Front element

---

## Question 14
Is it possible to create a doubly linked list using only one pointer with every node?

### Options:

A. ❌ Yes, possible by storing XOR of current node and previous node
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">
B. ❌ Not Possible
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">
C. ✅ Yes, possible by storing XOR of addresses of previous and next nodes
D. ❌ Yes, possible by storing XOR of current node and next node
<p style="margin-bottom:0cm;margin-bottom:.0001pt;line-height:

normal">
**Correct Answer:** Yes, possible by storing XOR of addresses of previous and next nodes

---

## Question 15
New elements are added to the……… of the QUEUE?

### Options:

A. ❌ Tap
B. ❌ Back
C. ✅ Rear
D. ❌ Front
**Correct Answer:** Rear

---

## Need Help?

If you're stuck on a question, need clarification, or believe there's an issue with the test, please don't hesitate to reach out!

<a href='mailto:ujjwaljha744@gmail.com?subject=Help%20Needed%20-%20CSE - Practice Test -14&body=Test%20ID%3A%206423077e435752649a8efed9%0A%0AQuestion%20Number%3A%20%0A%0ADescription%20of%20Issue%3A%20' style='display: inline-block; padding: 10px 20px; background-color: #4CAF50; color: white; text-decoration: none; border-radius: 5px;'>Report Issue / Ask for Help</a>

![Thank You](https://media.giphy.com/media/M9NbzZjAcxq9jS9LZJ/giphy.gif)

*Last updated: 2024-07-22 20:52:36*
