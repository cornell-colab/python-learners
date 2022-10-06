# Session 3
Instructors:
* Iliana Burgos, Emerging Data Practices Librarian (itb23)
* Devin Sanera, Instructional Technology Coordinator (ds895)

## Welcome, review of previous session, and questions (10 minutes)

* Any questions from last time?
* Algorithms + Data Structures = Programs
  * Today we will learn about the algorithm side of this formula

## Comparisons (10 minutes)
The result of these operations is either True or False, which are special boolean data types

* ==
  * 3 == 3 returns True
  * 3 == "3" returns False (checking equality between a numeric value and a string is False in Python, other languages may differ)
  * 3 == 3.0 returns True (checking equality between an integer and a float is fine in Python, other languages may differ)
* \>
  * Not limited to numeric values: "a" < "b" returns True, strings are compared lexicographically (lexicographical ordering is a mathematical generalization of alphabetical ordering)
  * However, there is likely a better way to accomplish the task of alphabetization, depending on the specific details of the operation
* <
* \>=
* <=
* !=

Experiment! Try different comparisons on your own.

### Logical operators to combine comparisons

The result of these operations is either True or False.

* and
  * &&
  * True and True evaluates to True
  * True and False evaluates to False
  * False and True evaluates to False
  * False and False evaluates to False

* or - also returns True if "and" is true.
  * ||
  * True or True evaluates to True
  * True or False evaluates to True
  * False or True evaluates to True
  * False or False evaluates to False

* not

* (xor) - exclusive "or", returns False if "and" is True
  * must use ^ symbol 

## Conditionals (10 minutes)
* if
```
if(True):
     run this code
```
* else
* elif

## Conclusion, discuss questions, and lessons learned (10 minutes)

* Think about how you could use conditionals and comparisons to evaluate, sort, or clean data from a list.

**Share out either of the following:**
* One interesting thing you learned
* One question you have
* Any concerns or unclear topics?
