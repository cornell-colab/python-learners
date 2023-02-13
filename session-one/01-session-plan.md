# Session 1
Instructors:
* Iliana Burgos, Emerging Data Practices Librarian (itb23)
* Devin Sanera, Instructional Technology Coordinator (ds895)

## Welcome, review of previous session, and questions (5 minutes)

* Any questions from last time?
* Differences between VisualStudio, PyCharm, JupyterLab, VSCode
  * Differences between an IDE vs text editor, how the computer is processing your code

## Variables and Data Types (35 minutes)

* Algorithms + Data Structures = Programs
  * Today we will learn about the data side of this formula

* If you have any questions about the structure of Python scripts or errors, refer to the following sections: 
  * [Anatomy of a Python script](https://melaniewalsh.github.io/Intro-Cultural-Analytics/02-Python/03-Anatomy-Python-Script.html) and 
  * [Common Python errors](https://melaniewalsh.github.io/Intro-Cultural-Analytics/02-Python/13-Common-Python-Errors.html)

### [Python variables](https://melaniewalsh.github.io/Intro-Cultural-Analytics/02-Python/04-Variables.html)
* A variable is a "container" for data. In Python, we create a new variable by assigning a value to it (other languages differ). If you've used a spreadsheet to run calculations, each cell can be a variable.
* Variables can be modified or overwritten by later code. It's not usually necessary to delete variables once they are no longer in use, the computer handles that.
* Plan ahead and try to name your variables well, names that are too short or generic will be more difficult to understand and follow when you review or modify your code later.
  * Use code comments too!

### [Python data types](https://melaniewalsh.github.io/Intro-Cultural-Analytics/02-Python/05-Data-Types.html)
* Single element data types:
  * Strings (Text)
  * Integers (Whole Numbers)
  * Floats (Decimal Numbers)
    * `print(1.03-0.42)`
  * Booleans (True/False)

* Checking types
  * type()

* Converting between types
  * int(), str(), float()

* Combining two items of the same type
  * Numerical types can be combined without conversion
    * `print(3+0.14)`
  * Strings can be concatinated with `+` operator, if you want a space you need to add it somewhere
    * `print("Olin" + "Library")`

* Multiple element data types (data structures):
  * Lists (an array of elements)
  * Other data types, we won't cover these today
    * Dictionaries (a unordered key-value structure)
    * Set (unordered, doesn't allow duplicates)
    * Tuple (ordered, not able to modify tuple contents)

* Addressing elements or ranges of elements within lists
  * list[0]
  * list[2:7]

* Structures can be nested. For example, a list can contain elements that are themselves other lists.
  * list[0][2]

* Modifying lists
  * append() - adds an item to the end of the list. If you are trying to merge two lists, append will put the entire list as one element.
  * extend() - extends the list, used for merging one list into another
    * can also use + if you want to create a new list out of two lists
  * insert() - inserts an item from the list at a specified postion
    * list[position] = new_element
  * pop() - removes an item from the list at a specified postion

* Returning to single element types
  * You can operate on strings in a very similar way to list elements
    * Consider the string "filename" defined by `filename = ScreenShot_22-03-16_11-12-21-000.jpg`
    * We can "select" only the part of the string containing the "hour" information like this: `hour = filename[20:22]`
    * How might we select the entire date? Are there other considerations to think about regarding this overall task that we should consider?

## Discuss questions and lessons learned (10 minutes)

**Share out either of the following:**
* An interesting thing you learned
* Any questions you have
