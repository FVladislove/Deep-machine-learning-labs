# Laboratory works on deep machine learning
### Because of some works might be based on previous, i decided not to create branches but update README with each subsequent laboratory work

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
Finally you can select kernel (venv in our case) and run file using VSCode or JupyterLab
## Tasks
Using Jupyter Notebook, create an application that asks the user for two
integers a and b, and then displays the results of the following mathematical operations on the screen:
- sum *a* and *b*
- difference between *a* and *b*
- multiply *a* and *b*
- fraction from division *a* and *b*
- remainder from division *a* and *b*
- decimal logarithm of *a*
- result of raising the number *a* to the power of *b*

### About requirements.txt
I installed only kernel to run jupiter file using VSCode, and it installed all these extensions. IDK why did it install such as **tornado**, but so be it