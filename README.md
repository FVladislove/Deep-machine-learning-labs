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
## Tasks (PW-7)
1. **Decision tree without params settings** <br/>
   Teach decision tree (DecisionTreeClassifier) with max depth 3 and evaluate precision indicator on test data. Use parameter `random_state=17` for results reproducibility. <br/>
   Make a precision with trained model.
2. **Decision tree with params settings**
   Teach decision tree (DecisionTreeClassifier, random_state=17). Find optimal max depth by using 5-times cross check (GridSearchCV) <br/>
   Teach decision tree with max depth 9 (the best `max_depth` in our case) and calculate precision test set. Use `random_state=17` for reproducibility.