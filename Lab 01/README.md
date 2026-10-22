# Lab 01: Introduction to Python Programming

**Course:** CS-3105 Machine Learning Lab
**Instructor:** Engr. Muhammad Awais
**Student:** Mahdi Ali
**Roll No:** 2024-SE-16
**CLO:** CLO 5 - Use Python programming and tools to perform data handling and basic operations (C-3 Apply, PLO 5 Modern Tool Usage)

## Overview

This lab is a first hands-on introduction to Python for machine learning. The notebook solves 10 short tasks on arithmetic, strings, nested indexing, collections and functions, plus 3 bonus challenges. No external libraries are needed.

## Files

| File | Description |
|---|---|
| `Lab 01_2024-SE-16_Mahdi Ali.ipynb` | Jupyter notebook with all tasks, bonus challenges and outputs |
| `README.md` | This file |

## Requirements

- Python 3.9 or higher
- Jupyter Notebook, JupyterLab, VS Code, or Google Colab
- No extra packages (only the standard library is used: `string`)

## How to Run

1. Open the notebook in Jupyter, VS Code or Google Colab.
2. Select **Runtime / Kernel -> Restart and run all**.
3. All cells should run from top to bottom without errors, with every output visible.

## Contents

| Task | Topic | Approach |
|---|---|---|
| 1 | Power | `7 ** 4` |
| 2 | String splitting | `s.split()` |
| 3 | String formatting | `"...{}...{}".format(planet, diameter)` |
| 4 | Nested list indexing | `lst[3][1][2][0]` |
| 5 | Nested dictionary indexing | `d['k1'][3]['tricky'][3]['target'][3]` |
| 6 | Tuple vs list | Written explanation plus a demo of mutability (`TypeError` on a tuple) |
| 7 | Email domain function | `email.split("@")[1]` |
| 8 | Is "dog" in a string? | Lower-case the text, then `in` |
| 9 | Count "dog" in a string | Lower-case the text, then `.count("dog")` |
| 10 | `caught_speeding(speed, is_birthday)` | Subtract 5 from the speed on a birthday, then use `if / elif / else` thresholds |

### Bonus Challenges

| Bonus | Description |
|---|---|
| 1 | `count_dog_punct`: counts "dog" even with punctuation (`dog,`, `dog!`) by stripping punctuation from each word |
| 2 | `is_palindrome(word)`: uses slicing `word[::-1]` |
| 3 | List of 5 student dictionaries; finds and prints the topper's name |

## Notebook Format

- A text cell labelled "Task N" sits above each code cell.
- Outputs are labelled, e.g. `Q1: 2401`.
- Functions have docstrings and comments, and variable names are meaningful.

## Sample Output

```
Q1: 7 ** 4 = 2401
Q2: ['Hi', 'there', 'Sam!']
Q3: The diameter of Earth is 12742 kilometers.
Q4: hello
Q5: hello
Q7: domain.com
Q10: Small Ticket      # caught_speeding(81, True)
Bonus 3: Topper is Ayesha with CGPA 3.9
```

## Notes

- Task 8 and Task 9 are case-insensitive and match "dog" as a substring, so "dogs" also counts. Bonus 1 matches whole words only.
- In Task 10, a birthday gives 5 extra mph: a speed of 65 on a birthday is treated as 60 (No Ticket).
