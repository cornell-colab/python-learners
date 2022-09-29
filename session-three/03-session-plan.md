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

## for() loops (15 minutes)
* There are many ways to use a for() loop, one of the most powerful ways is to interate through a list.
* In part of the set-up, you decide what to name the variable that will hold each list element for each single run of the loop.
* In this example, "number" is not a variable used elsewhere, we are defining it right here. "number" will take on the values 1, 2, 3, 4 in sequence for each run of the loop. The result of this output is the sequence 2, 3, 4, 5.

```
list = [1, 2, 3, 4]
for number in list:
  print(number + 1)
```

## Conclusion, discuss questions, and lessons learned (10 minutes)

* Think about how you could use a for() loop with conditionals and comparisons inside the loop to evaluate, sort, or clean data from a list element-by-element.

**Share out either of the following:**
* One interesting thing you learned
* One question you have
* Any concerns or unclear topics?
