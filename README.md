# Advanced Computer Programming and Algorithms 

## Experiment 2: Numpy

Name: Clarence Jasper S. Gaspar      

Section: 2ECE-B

---

**Overview**

This repository is created to showcase various programming activities, specifically Python programming. It will serve both as a submission bin and a portfolio for Advanced Computer Programming and Algorithms. All activities are developed using Jupyter Notebook (Anaconda) and then exported and uploaded here to GitHub. Each activity demonstrates different Python concepts, functions, and problem-solving approaches in the course.
<br><br>



📌 **Tools Used**

*Anaconda* – to manage Python environments and launch Jupyter Notebook.

*Jupyter Notebook* – to write, run, and test Python programs interactively.

*GitHub* – to store and showcase the Python programming activities.
<br><br>



📝 **Workflow**

1. Write Code in Jupyter Notebook

    - Open Jupyter Notebook from Anaconda Navigator.

    - Create a python(.ipynb) file for each activity.

    - Use functions, loops, and other Python concepts to solve tasks.

2. Export Activity

    - Save work as .ipynb which is the default Jupyter format.

3. Upload to GitHub

    - Create a new repository in GitHub.

    - Upload the .ipynb file(s) to the repository.
  
    - Aside from .ipynb file, .npy file was also uploaded as part of the Module 2.1(numpy)

4. Organize Portfolio

    - Each activity will have its own repository and own section of README.
    - Tasks will be documented with short explanations and screenshots.


<br><br>

---

📂 **Activities**

The original files for these activities are uploaded in this repository alongside this README file. Each activity is written in Python and can be previewed directly on GitHub using its notebook preview feature. However, to fully run the programs and provide inputs, the files should be imported into coding platforms such as Jupyter Notebook from Anaconda. The Python codes already contain short comments denoted by # to guide readers through the logic. Furthermore, the information below provides additional explanations to further clarify how each part of the program works.

---

🔹 *Experiment 2: NUMERICAL PYTHON (NUMPY)*

**I. Intended Learning Outcomes:**
<br><br> 
    1. To identify the codes and functions incorporated in the Numpy library.
<br>   
    2. To be able to apply and use the different codes and functions in creating a Python program using a Numpy library.
<br><br> 

**II. Instructions:**

Write a Python script/code in the Jupyter Notebook to do the given problems.


- **Task 1: Normalization Problem:**
  
<img width="1397" height="755" alt="Screenshot 2025-09-03 030854" src="https://github.com/user-attachments/assets/2f8aeac4-cd76-4e87-a9d8-f2ab4596d49d" />


This part demonstrates how to generate a random 5×5 NumPy array, calculate its mean and standard deviation, and then normalize the dataset using these statistical values. Normalization is an important preprocessing step in data science and machine learning because it scales data into a standard range, making it easier to compare values. The task also includes saving the normalized array into a .npy file for future use, showing how NumPy can efficiently handle both computation and file storage.

### Code Explanation

```
import numpy as np
```
This section of the code imports the Numpy library with a nickname np to allow it to be called easier. This will be used for generating arrays and doing calculations.

```
X = np.random.random((5,5))
```
This section creates a 5x5 array of random values between 0 and 1 under the variable name "X".

```
print("Original X:\n", X)
```
This prints the generated array to the console. The `\n` ensures the array is shown on a new line.

```
X_mean = X.mean()
```
This calculates the mean of all elements in the array. The result is stored in the variable `X_mean`.

```
X_std = X.std()
```
This calculates the standard deviation of the array. The result is stored in the variable `X_std`.

```
X_normalized = (X - X_mean) / X_std
```
This normalizes the array by subtracting the mean and dividing by the standard deviation. The result is stored in `X_normalized`.

```
print("\nMean of X:", X_mean)
print("Standard Deviation of X:", X_std)
print("Normalized X:\n", X_normalized)
```
These lines print the mean, standard deviation, and the normalized array.

```
np.save("X_normalized.npy", X_normalized)
```
This saves the normalized array into a `.npy` file. It allows the data to be reused without recalculation.

<br><br>


- **Task 2: Divisible by 3 Problem:**

<img width="1395" height="705" alt="Screenshot 2025-09-03 063433" src="https://github.com/user-attachments/assets/1223dff1-5109-41d0-88de-74972e4c1fe2" />


This activity demonstrates how to generate a 10×10 NumPy array containing the squares of the first 100 positive integers. It also applies boolean indexing to extract all values divisible by 3, and saves the result into a .npy file for later use.


