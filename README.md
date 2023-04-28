# Practical works on deep machine learning
### UPD. Eventually, I decided to create new brunches because it is easier to swap between practical works, but I will be merging all changes to **master** to view and show my skill growth

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
## Tasks (PW-4)

1. Write function for converting dictionary to Pandas series.
2. Write function to convert array ro Pandas series.
3. Write function to insert some data to series.
4. There are next data:
    ```python
    data = {'animal': ['cat', 'cat', 'snake', 'dog', 'dog', 'cat', 'snake', 'cat', 'dog', 'dog'],
            'age': [2.5, 3, 0, 5, np.nan, 5, 2, 4.5, np.nan, 7, 3],
            'visits': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1],
            'priority': ['yes', 'yes', 'no', 'yes', 'no', 'no', 'no', 'yes', 'no', 'no']
            }
    labels = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j']
    ```
    Create DataFrame from this data, which have *labels* as indexes.
    Then do this tasks: 
    - select only *animal* and *age* from DF
    - select data from rows [3, 4, 8] and cols ['animal', 'age']
    - select rows, where visits count greater than 3
    - select rows, where animal - cat and age lower then 3
    - select rows, where age between 2 and 4 (include)
    - calculate sum of all visits
    - add new row 'k' to DF with value choosing for every column. Then delete this row to return output DF 