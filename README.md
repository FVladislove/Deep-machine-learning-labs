# Practical works on deep machine learning
### Because some works might be based on previous, I decided not to create branches but update README with each subsequent practical work

## Installation and startup (Windows)
At first you need to clone repo to selected folder
```bash
git clone https://github.com/FVladislove/Deep-machine-learning-labs.git
cd Deep-machine-learning-labs
```
Next you must create virtual environment and activate it
```bash
python3 -m venv venv
venv/Scripts/activate
```
Then you must install required modules
```bash
pip install -r requirements.txt
```
Finally, you can select kernel (venv in our case) and run the file using VSCode or JupyterLab
## Tasks
Write a program that performs the following operations:
1. Element-wise addition of two one-dimensional arrays, a1 and a2, of given size N. Elements of the array a1: numbers equally distributed in the range from 0 to 100. Elements of the array a2: numbers evenly distributed in the interval from 0 to 1
2. Matrix multiplication: m1 and m2, with a given number of rows and columns. Elements in each column of the matrix m1: an element of the array a1. Elements in each row of matrix m2: elements from array a2.
 
All arrays must be of type ndarray. The dimensions of the arrays and the matrix are arbitrary and are given as parameters. Filling the matrices m1 and m2 with values should be carried out using the operation of slices of arrays. Operations 1 and 2 must be implemented in two ways: directly using for loops and using the capabilities of the NumPy library, which allow you to perform operations on arrays.

### My thoughts
#### About filling matrix
I think, that carrying out filling the matrices using array slices is not that good because: if the user input a number of row or column, that bigger than the array from which we took the data, we need to repeat this operation again (using *for* (or *map*, I have not explored this option) or prevent user to input greater number. I think, that my method of filling the matrix is great (but maybe not that readable, so I added an explanation) and if you wanna fill the matrix with random numbers from an array in future, you should do minimal changes to existed code.
#### About matrix multiplication
It is hard to understand what *matrix multiplication* really means in the context of given practical work, because *[ndarray].prod()* and *[ndarray] * [ndarray]* were shown to as, but with no example with matrix, and none of does not fit what is usually mean **matrix multiplication**. So I decided to implement the option that I consider more correct.

### About requirements.txt
I installed only kernel to run jupiter file using VSCode, and it installed all these extensions. IDK why did it install such as **tornado**, but so be it