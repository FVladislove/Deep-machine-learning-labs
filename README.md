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
## Tasks (PW-6)
For the task implementation will be used dataset "Titanic train" about "Titanic" ship passengers. First get acquainted with dataset features, after done next tasks: 
1. Delete feature `Cabin` and then all rows with omissions. Then build pairwise dependencies of features `Age, Fare, Pclass, Sex, SibSp, Parch, Embarked, Survived` using function `scatter_matrix` from Pandas library or method `pairplot` from Seaborn
2. Build `boxplot` that reflects dependency from ticket fee on the cabin class (Pclass).
Optional: create new `Fare_no_out` which excludes costs, that are different from mean by class more over 2 standard deviation. Important: must be excluded emissions in dependency from cabin class. Otherwise excludes only the biggest (1 class) and small (3 class) costs.
3. Display correlation between dead and survivors depending on gender using `Seaborn.countplot` and argument `hue`
4. Display correlation between dead and survivors depending on cabin class using `Seaborn.countplot` and argument `hue`
5. Which surviving fact depends on passenger age? Check (graphically) assumption that young survived more often. Let, conditionally, young - before 30 years old, old - after 60.
