<!-- Markdown content below -->

# 📚 CSE - Mock Test - 06 🚀

![Animated GIF](https://media.giphy.com/media/l0HlNaQ6gWfllcjDO/giphy.gif)

**Test ID:** `64230c43435752ea71929e0d` :id:
**Total Questions:** `20` 🧮
**Total Time:** `35 minutes` :hourglass_flowing_sand:

---

## 🔥 Question 1 🧠 🤔

A special redo-only log record &lt;Ti , Xj , V1&gt; is written to the log, where V1 is the value being restored to data item Xj during the rollback. These log records are sometimes called_

### 📋 Options:
- A. 🔴 Log records
- B. 🟢 Compensation log records
- C. 🔴 Compensation redo records
- D. 🔴 Records

**⭐ Correct Answer:** 🎯 `Compensation log records`

✨ --- ✨ --- ✨

## 🔥 Question 2 🧠 🤔

<pre>

<span><span lang="EN-US" style='font-family:



"Arial",sans-serif'>SELECT</span></span><span lang="EN-US" style='font-family:



"Arial",sans-serif'> course_id</span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>FROM</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> <span>SECTION</span></span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>WHERE</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> semester <span>=</span> ’Fall’ <span>AND</span> <span>YEAR</span><span>=</span> <span>2009</span><span>)</span></span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>EXCEPT</span></span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>(</span></span><span><span lang="EN-US" style='font-family:"Arial",sans-serif'>SELECT</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> course_id</span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>FROM</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> <span>SECTION</span></span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>WHERE</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> semester <span>=</span> ’Spring’ <span>AND</span> <span>YEAR</span><span>=</span> <span>2010</span><span>)</span>;</span></pre>
This query displays ______

### 📋 Options:
- A. 🔴 Only tuples from the first part which has the tuples from second part
- B. 🟢 Tuples from first part which do not have second part
- C. 🔴 Tuples from both the parts
- D. 🔴 Only tuples from second part

**⭐ Correct Answer:** 🎯 `Tuples from first part which do not have second part`

✨ --- ✨ --- ✨

## 🔥 Question 3 🧠 🤔

The union operation automatically __________, unlike the select clause._

### 📋 Options:
- A. 🟢 Eliminates duplicate
- B. 🔴 Adds common tuples
- C. 🔴 Adds tuples
- D. 🔴 Eliminates unique tuples

**⭐ Correct Answer:** 🎯 `Eliminates duplicate`

✨ --- ✨ --- ✨

## 🔥 Question 4 🧠 🤔

Which of the following statement(s) is/are FALSE in the context of Relational DBMS ?
I. Views in a database system are important because they help with access control by allowing users to see only a particular subset of the data in the database.
II. E-R diagrams are useful to logically model concepts.
III. An update anomaly is when it is not possible to store information unless some other, unrelated information is stored as well.
IV. SQL is a procedural language._

### 📋 Options:
- A. 🔴 I and IV only
- B. 🟢 II, III and IV only
- C. 🔴 III and IV only
- D. 🔴 I, II and III only

**⭐ Correct Answer:** 🎯 `II, III and IV only`

✨ --- ✨ --- ✨

## 🔥 Question 5 🧠 🤔

<pre>

<span><span lang="EN-US" style='font-family:



"Arial",sans-serif'>CREATE</span></span><span lang="EN-US" style='font-family:



"Arial",sans-serif'> <span>TABLE</span> course</span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>(</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> <span>.</span> <span>.</span> <span>.</span></span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>FOREIGN</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> <span>KEY</span> <span>(</span>dept_name<span>)</span> <span>REFERENCES</span> department</span></pre>
<pre>

<span><span lang="EN-US" style='font-family:"Arial",sans-serif'>.</span></span><span lang="EN-US" style='font-family:"Arial",sans-serif'> <span>.</span> <span>.</span> <span>)</span>;</span></pre>
Which of the following is used to delete the entries in the referenced table when the tuple is deleted in course table?_

### 📋 Options:
- A. 🟢 Delete cascade
- B. 🔴 Set null
- C. 🔴 Delete
- D. 🔴 All of the mentioned

**⭐ Correct Answer:** 🎯 `Delete cascade`

✨ --- ✨ --- ✨

## 🔥 Question 6 🧠 🤔

<pre>

<span><span lang="EN-US" style='font-family:



"Arial",sans-serif'>CREATE</span></span><span lang="EN-US" style='font-family:



"Arial",sans-serif'> <span>TABLE</span> Manager<span>(</span>ID <span>NUMERIC</span><span>, </span>Name <span>VARCHAR</span><span>(</span><span>20</span><span>)</span><span>, </span>budget <span>NUMERIC</span><span>, </span>Details <span>VARCHAR</span><span>(</span><span>30</span><span>))</span>;</span></pre>
Inorder to ensure that the value of budget is non-negative, which of the following should be used?_

### 📋 Options:
- A. 🔴 Check(budget&lt;0)
- B. 🔴 Alter(budget&lt;0)
- C. 🔴 Alter(budget&gt;0)
- D. 🟢 Check(budget&gt;0)

**⭐ Correct Answer:** 🎯 `Check(budget&gt;0)`

✨ --- ✨ --- ✨

## 🔥 Question 7 🧠 🤔

The current copy of the database is identified by a pointer, called ____________ which is stored on disk._

### 📋 Options:
- A. 🟢 Db-pointer
- B. 🔴 All of the mentioned
- C. 🔴 Update log
- D. 🔴 Update log records

**⭐ Correct Answer:** 🎯 `Db-pointer`

✨ --- ✨ --- ✨

## 🔥 Question 8 🧠 🤔

Which of the following is not a integrity constraint ?_

### 📋 Options:
- A. 🔴 Not null
- B. 🟢 Positive
- C. 🔴 Unique
- D. 🔴 Check ‘predicate’

**⭐ Correct Answer:** 🎯 `Positive`

✨ --- ✨ --- ✨

## 🔥 Question 9 🧠 🤔

Relation R has eight attributes ABCDEFGH. Fields of R contain only atomic values. F = {CH -&gt; G, A -&gt; BC, B -&gt; CFH, E -&gt; A, F -&gt; EG} is a set of functional dependencies (FDs) so that F+ is exactly the set of FDs that hold for R.
How many candidate keys does the relation R have?_

### 📋 Options:
- A. 🔴 5
- B. 🟢 4
- C. 🔴 3
- D. 🔴 6

**⭐ Correct Answer:** 🎯 `4`

✨ --- ✨ --- ✨

## 🔥 Question 10 🧠 🤔

The actions which are played in the order while recording it is called ______________ history?_

### 📋 Options:
- A. 🔴 Replay
- B. 🔴 Redo
- C. 🔴 Undo
- D. 🟢 Repeating

**⭐ Correct Answer:** 🎯 `Repeating`

✨ --- ✨ --- ✨

## 🔥 Question 11 🧠 🤔

_______________ provides option for entering SQL queries as execution time, rather than at the development stage._

### 📋 Options:
- A. 🔴 PL/SQL
- B. 🟢 Dynamic SQL
- C. 🔴 SQL*Plus
- D. 🔴 SQL

**⭐ Correct Answer:** 🎯 `Dynamic SQL`

✨ --- ✨ --- ✨

## 🔥 Question 12 🧠 🤔

In order to maintain transactional integrity and database consistency, what technology does a DBMS deploy?_

### 📋 Options:
- A. 🔴 Triggers
- B. 🟢 Locks
- C. 🔴 Cursors
- D. 🔴 Pointers

**⭐ Correct Answer:** 🎯 `Locks`

✨ --- ✨ --- ✨

## 🔥 Question 13 🧠 🤔

The relation book (title,price) contains the titles and prices of different books. Assuming that no two books have the same price, what does the following SQL query list?
select title
from book as B
where (select count(*)
from book as T
where T.price&gt;B.price)&lt;5_

### 📋 Options:
- A. 🔴 Title of the fifth most inexpensive book
- B. 🔴 Titles of the four most expensive books
- C. 🔴 Title of the fifth most expensive book
- D. 🟢 Titles of the five most expensive books

**⭐ Correct Answer:** 🎯 `Titles of the five most expensive books`

✨ --- ✨ --- ✨

## 🔥 Question 14 🧠 🤔

The maximum number of superkeys for the relation schema R(E,F,G,H) with E as the key is_

### 📋 Options:
- A. 🔴 5
- B. 🔴 7
- C. 🔴 6
- D. 🟢 8

**⭐ Correct Answer:** 🎯 `8`

✨ --- ✨ --- ✨

## 🔥 Question 15 🧠 🤔

What is the output of the following SQL query?
select count(*) from ((select Employee, Department from Overtime_allowance) as S
natural join (select Department, OT_allowance from Overtime_allowance) as T);_

### 📋 Options:
- A. 🔴 none
- B. 🔴 None of the above
- C. 🔴 8
- D. 🔴 16
- E. 🟢 4

**⭐ Correct Answer:** 🎯 `4`

✨ --- ✨ --- ✨

## 🔥 Question 16 🧠 🤔

Selecting the victim to be roll backed to the previous state is determined by the minimum cost. The factors determining cost of rollback is_

### 📋 Options:
- A. 🔴 How many more data items the transaction needs for it to complete
- B. 🟢 All of the mentioned
- C. 🔴 How long the transaction has computed, and how much longer the transaction will compute before it completes its designated task
- D. 🔴 How many data items the transaction has used

**⭐ Correct Answer:** 🎯 `All of the mentioned`

✨ --- ✨ --- ✨

## 🔥 Question 17 🧠 🤔

DFD stands for__________._

### 📋 Options:
- A. 🔴 Data File Diagram
- B. 🔴 Data Flow Document
- C. 🟢 Data Flow Diagram
- D. 🔴 None of the above

**⭐ Correct Answer:** 🎯 `Data Flow Diagram`

✨ --- ✨ --- ✨

## 🔥 Question 18 🧠 🤔

The subset of super key is a candidate key under what condition?_

### 📋 Options:
- A. 🔴 Subset is a super key
- B. 🔴 All subsets are super keys
- C. 🟢 No proper subset is a super key
- D. 🔴 Each subset is a super key

**⭐ Correct Answer:** 🎯 `No proper subset is a super key`

✨ --- ✨ --- ✨

## 🔥 Question 19 🧠 🤔

Which one of the following provides the ability to query information from the database and to insert tuples into, delete tuples from, and modify tuples in the database?_

### 📋 Options:
- A. 🔴 DDL(Data Definition Langauge)
- B. 🔴 Relational Schema
- C. 🟢 DML(Data Manipulation Langauge)
- D. 🔴 Query

**⭐ Correct Answer:** 🎯 `DML(Data Manipulation Langauge)`

✨ --- ✨ --- ✨

## 🔥 Question 20 🧠 🤔

Consider the following two tables and four queries in SQL.
Book (isbn, bname), Stock (isbn, copies)
Query 1:
SELECT B.isbn, S.copies
FROM Book B INNER JOIN Stock S
ON B.isbn = S.isbn;
Query 2:
SELECT B.isbn, S.copies
FROM B B LEFT OUTER JOIN Stock S
ON B.isbn = S.isbn;
Query 3:
SELECT B.isbn, S.copies
FROM Book B RIGHT OUTER JOIN Stock S
ON B.isbn = S.isbn;
Query 4:
SELECT B.isbn, S.copies
FROM B B FULL OUTER JOIN Stock S
ON B.isbn = S.isbn;
Which one of the queries above is certain to have an output that is a superset of the outputs of the other three queries?_

### 📋 Options:
- A. 🔴 Query 3
- B. 🔴 Query 2
- C. 🟢 Query 4
- D. 🔴 Query 1

**⭐ Correct Answer:** 🎯 `Query 4`

✨ --- ✨ --- ✨

## :sos: Need Help? ✋

💬 If you encounter any issues or have questions, please don't hesitate to reach out!

🔗 [Report an Issue](https://example.com/report-issue)

![Thank You](https://media.giphy.com/media/3o6Zt6KHxJTbXCnSvu/giphy.gif)

:clock10: *Last updated: 2024-07-22 18:09:20*
