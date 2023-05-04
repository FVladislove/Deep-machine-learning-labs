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
## Tasks (PW-5)
Get acquainted with dataset 'Adult' and answer questions:
1. How many men and women are represented in the dataset? 
2. Women's average age?
3. Percentage of German citizens?
4. Average value and standard deviation for those who earn more than 50 thousand per year.
5. Average value and standard deviation for those who earn less than 50 thousand per year.
6. Is that true, that people who earn more than 50 t/year have at least secondary education (Bachelor, Prof-school, Doctorate, Masters, Assoc-voc, Assoc-acdm)
7. Display age statistics for every race and sex. Use ***groupby()*** and ***describe()***. Find the maximum age of the american-indian-Eskimo race.
8. Among whom is the greater share of those earning a lot (>50 t.): married or single men? Consider those with a marital status beginning from ***Married***
9. What is the max number of hours a person works a week? How many people work such, and what percentage of them are those who earn a lot (>50 t.)
10. Calculate the average work time (hours per week) for low and high earners for each country. What will it be for Japan?