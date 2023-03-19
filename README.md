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
## Tasks (PW-3)
Modify the graph plotting program, which is given in the methodological part of practical work, according to followed requirements:
1. Remove the image title, grid and legend
2. Draw a graph of each of the four functions on a separate drawing panel. The axis of each panel must be signed. On the top centre of each panel should be added text mark: 
    - "(a)" for panel 1
    - "(b)" for panel 2
    - "(c)" for panel 3
    - "(d)" for panel 4
3. The sinus graph should be plotted using a solid black line, cosine — a dotted red line, sinus squared — a dashed black line, and x^0.15 — a solid grey line.
4. Set the x-axis diapason in each panel between 0 and 2π. The y-axis diapason should be such that graph of relevant functions might be viewed fully.