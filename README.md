<!--
author:   André Dietrich

email:    LiaScript@web.de

version:  0.0.1

language: en

narrator: US English Female

import: https://raw.githubusercontent.com/LiaScript/CodeRunner/master/README.md

-->

[![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/SebastianZug/PythonCourse_2023/main/README.md#1)

# Python Summer School 2023 - Part B - 2th September

Organizers and Lectureres 

+ Yekaterina Strigina
+ Sebastian Zug (TU Bergakademie Freiberg)


------------------------------------------------------------

## Organisation

__Agenda of this day__

| Slot          | Topic                                                      |
|---------------|----------------------------------------------------------- |
| 10:00 - 11:15 | Review, comparison of Jupyter notebooks and Python scripts |
| 11:30 - 12:45 | Introduction to image processing based on opencv           |
| 12:45         | Lunch                                                      |
| 13:30 - 14:45 | Basics of data analysis using pandas                       |
| 15:00 - 16:15 | Visualisation of pandas data frames                        |

### Preparation

__Step 1:__ Please install the following Python packages on your maschine:

+ opencv - `pip install opencv-python`
+ pandas - `pip install pandas`

__Step 2:__ Additionally, it is necessary to add the [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
package to your Visual Studio Code environment. 

!?[](https://www.youtube.com/watch?v=ei-WirjwtOM)

__Step 3:__ Check the correctness of the implementation by opening a new file (shown in the move above) and adding the following code

```
import pandas as pd

pd.__version__
```

If something like `'1.5.0'` appears everything is fine. In case of `ModuleNotFoundError: No module named 'pandas'` check the installation outputs of Step 1.

__Step 4:__ Generate an ChatGPT account - we will use the AI for boosting our programming activities.

### Warm up

> __Task:__ Implement a python class `complex_calc` containing a list of entrys `value_list` and a method `multiply_list(multiplyer)`. The program initiates an instance of the class, reads the input of a user, calls the `multiply_list` methods.

> __Hint:__ Use [ChatGPT](https://www.bing.com/search?q=Bing+AI&showconv=1&FORM=hpcodx) or any other AI to fasten up your coding. 
> 
> ![An Atlas-Agena 5 carrying the Mariner 1 spacecraft](./images/ChatGPT_Python_script.png)

{{1}}
```python Solution.py
# Object definition
class complex_calc:
    def __init__(self, value_list):
        self.value_list = value_list

    def multiply_list(self, multiplier):
        return [multiplier * i for i in self.value_list]

# Initialization of an object instance
my_list = [1, 2, 3, 4]
my_instance = complex_calc(my_list)

# Apply mathmatical operation
multiplier = 2
result = my_instance.multiply_list(multiplier)

print(result)  
```
@LIA.eval(`["main.py"]`, `none`, `python3 main.py`)

## Session 1 - Review, comparison of Jupyter notebooks and Python scripts 


## Session 2 - Introduction to image processing based on opencv 


## Session 3 - Basics of data analysis using pandas 


## Session 4 - Visualisation of pandas data frames