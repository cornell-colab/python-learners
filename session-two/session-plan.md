# Session 2

Instructors:
* Iliana Burgos, Emerging Data Practices Librarian (itb23)
* Devin Sanera, Instructional Technology Coordinator (ds895)

## Welcome, review of previous session, and questions (10 minutes)

* Any questions from last time?
* Algorithms + Data Structures = Programs
     * Now that we know about algorithms and data structures, it's time to write programs!

## Opening a file and importing data (5 minutes)
* `with open` opens the file in a safe way, meaning if there is an error or problem, the file will be closed automatically
    * There are other ways to open files where you have to explicitly close the file and in general these methods should be avoided.
* `encoding="utf-8"` - be aware of text encodings, this file will not import properly without this parameter.

## for() loops (15 minutes)
* There are many ways to use a for() loop, one of the most powerful ways is to interate through a list.
* In part of the set-up, you decide what to name the variable that will hold each list element for each single run of the loop.
* In this example, "number" is not a variable used elsewhere, we are defining it right here. "number" will take on the values 1, 2, 3, 4 in sequence for each run of the loop. The result of this output is the sequence 2, 3, 4, 5.

```
list = [1, 2, 3, 4]
for number in list:
  print(number + 1)
```

## Evaluating data with comparisons, conditionals, and loops (15 minutes)

* The [in keyword](https://docs.python.org/3.9/reference/expressions.html#membership-test-operations) tests for membership.
     * `x in string` tests if _x_ is exactly equal to _string_ **or any substring** of _string_ (partial matching)
     * `x in list` tests if _x_ is exactly equal to any element of _list_, **no partial matching of individual elements**


## Comparisons
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

## Conditionals
* if
```
if(True):
     run this code
```
* else
* elif

## Conclusion, discuss questions, and lessons learned (10 minutes)

### Opportunities for further learning:

#### Tutorials for digital humanists

* [Introduction to Cultural Analytics & Python, Version 1 (Walsh, 2021)](https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html):
 * [Analyze tabular data with Pandas](https://melaniewalsh.github.io/Intro-Cultural-Analytics/03-Data-Analysis/00-Data-Analysis.html)
 * [Collecting data from the web](https://melaniewalsh.github.io/Intro-Cultural-Analytics/04-Data-Collection/00-Data-Collection.html)
 * [Text analysis methods](https://melaniewalsh.github.io/Intro-Cultural-Analytics/05-Text-Analysis/00-Text-Analysis.html)
* [Python documentation](https://docs.python.org/3/)
* [W2Schools Online Web Tutorials](https://docs.python.org/3/)
* [Programming Historian](https://programminghistorian.org)

#### For library staff:

* [Python for Librarians (Library Carpentry)](https://librarycarpentry.org/library-python/)
* [Python lessons for librarians (Janowiecki, 2021)](https://gitlab.com/mjanowiecki/python-lessons-for-librarians/-/wikis/home)

**Share out either of the following:**
* One interesting thing you learned
* One question you have
* Any concerns or unclear topics?
