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

4. Organize Portfolio

    - Each activity will have its own section in this README.
    - Tasks will be documented with short explanations and screenshots.


<br><br>

---

📂 **Activities**

The original files for these activities are uploaded in this repository alongside this README file. Each activity is written in Python and can be previewed directly on GitHub using its notebook preview feature. However, to fully run the programs and provide inputs, the files should be imported into coding platforms such as Jupyter Notebook from Anaconda. The Python codes already contain short comments denoted by # to guide readers through the logic. Furthermore, the information below provides additional explanations to further clarify how each part of the program works.

---

🔹 *Activity 1: INTRODUCTION TO PYTHON PROGRAMMING*

**I. Intended Learning Outcomes:**
<br><br> 
    1. To identify the basic codes and functions in Python Programming.
<br>   
    2. To be able to apply the different codes and functions in creating a python program.
<br><br> 

**II. Instructions:**

Write a Python script/code in the Jupyter Notebook to do the given problems.


- **Task 1: Alphabet Soup Problem:**
  
<img width="1672" height="370" alt="Screenshot 2025-08-27 210230" src="https://github.com/user-attachments/assets/cd91fe53-350b-4b33-b1e1-36341b4b197d" />
  
  The program defines a function called arrange that takes a string and arranges its letters alphabetically. This is done by using sorted() to order the characters and join() to combine them back into a single string. The user is then asked to input a word, which is passed to the function. Finally, the arranged letters are displayed, showing the word’s characters sorted from A to Z.


- **Task 2: Emoticon Problem:**

<img width="1392" height="634" alt="Screenshot 2025-08-27 210334" src="https://github.com/user-attachments/assets/4d82a3c7-edd5-4d1f-b8ec-2d1cd4ba502a" />

  The program defines a function called convert that changes specific words in a sentence into their corresponding emoticons. A dictionary is used to store the word–emoticon pairs, such as “smile” → :) and “sad” → :((. The sentence is split into individual words, and the function checks each one to see if it matches a key in the dictionary. If it does, the word is replaced with the corresponding emoticon. After processing, the words are joined back into a complete sentence. The program demonstrates this with an example and then allows the user to enter their own sentence, which is converted into emoticons and displayed as output.

- **Task 3: Unpacking List Problem:**

<img width="1673" height="486" alt="Screenshot 2025-08-27 210354" src="https://github.com/user-attachments/assets/b00845de-23d5-4993-bd4a-2277d0589e4a" />

  The program starts with a list of numbers and demonstrates how to access specific elements using their indexes. The first element is obtained with list[0], since indexing begins at zero. The middle portion is extracted with list[1:-1], which selects all elements from the second up to the second-to-last. The last element is accessed using list[-1], where negative indexing counts from the end of the list. Finally, the program prints the first, middle, and last parts separately, showing how list slicing and indexing can classify elements based on their placement.
