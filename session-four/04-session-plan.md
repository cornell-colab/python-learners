# Session 4

Instructors:
* Iliana Burgos, Emerging Data Practices Librarian (itb23)
* Devin Sanera, Instructional Technology Coordinator (ds895)

## Welcome, review of previous session, and questions (10 minutes)

* Any questions from last time?
* Algorithms + Data Structures = Programs
      * Now that we know about algorithms and data structures, it's time to write programs!

## Opening a file and importing data (10 minutes)
* `with open` opens the file in a safe way, meaning if there is an error or problem, the file will be closed automatically
    * There are other ways to open files where you have to explicitly close the file and in general these methods should be avoided.
* `encoding="utf-8"` - be aware of text encodings, this file will not import properly without this parameter.

## for() loops (10 minutes)
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

## Conclusion, discuss questions, and lessons learned (10 minutes)

**Share out either of the following:**
* One interesting thing you learned
* One question you have
* Any concerns or unclear topics?
