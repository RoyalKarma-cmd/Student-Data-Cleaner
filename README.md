# Student Data Cleaner

## Project Overview

Student Data Cleaner is a Python project that demonstrates the use of **Lists, Sets, Loops, and Basic Data Analysis** to clean duplicate student records.

In real-world datasets, duplicate entries are common and can lead to incorrect analysis. This project removes duplicate student names, displays unique records, identifies duplicate entries, and provides useful statistics.

This project is part of my Data Science learning journey.

---

## Features

### Display Original Student Records

Shows all student names, including duplicates.

### Remove Duplicate Records

Uses Python Sets to automatically remove duplicate student names.

### Display Unique Students

Shows the cleaned list containing only unique student names.

### Display Duplicate Names

Identifies and displays student names that appear more than once.

### Generate Statistics

Displays:

* Total Student Entries
* Unique Student Entries
* Number of Duplicate Records Removed

---

## Concepts Used

### Python Concepts

* Lists
* Sets
* Loops (`for`)
* Conditions (`if`)
* Variables
* Built-in Functions

  * `len()`
  * `count()`
  * `set()`

### Data Science Concepts

* Data Cleaning
* Duplicate Detection
* Data Preprocessing
* Basic Data Analysis

---

## Sample Dataset

```python
student = [
    "Jaydeep",
    "Bhumi",
    "Shantanu",
    "Swayam",
    "Bhumi",
    "Jaydeep"
]
```

---

## Sample Output

```text
Original Students: 6
Unique Students: 4
Removed Data: 2

Unique Student Names:
Jaydeep
Bhumi
Shantanu
Swayam

Duplicate Names:
Jaydeep
Bhumi
```

---

## How It Works

### Step 1

Store student names inside a list.

### Step 2

Convert the list into a set.

```python
unique_students = set(student)
```

Sets automatically remove duplicate values.

### Step 3

Calculate statistics.

```python
duplicates_removed = len(student) - len(unique_students)
```

### Step 4

Identify duplicate student names.

```python
if student.count(name) > 1:
```

Names appearing more than once are stored and displayed.

---

## Learning Outcomes

Through this project, I learned:

* Difference between Lists and Sets
* How Sets remove duplicate values
* How to identify duplicate records
* Basic data cleaning techniques
* How real-world datasets are prepared before analysis

---

## Future Improvements

* Menu-driven version
* Add student records through user input
* Save cleaned data to a file
* Export cleaned data to CSV
* Search for a student
* Sort student names alphabetically
* Create a GUI version using Tkinter

---

## Why This Project Matters

Data Scientists spend a significant amount of time cleaning data before analysis.

This project simulates one of the most common preprocessing tasks:

✔ Removing duplicate records

✔ Identifying repeated values

✔ Preparing clean data for analysis

---

## Author

**Jaydeep**

