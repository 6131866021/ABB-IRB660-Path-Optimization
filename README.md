# ABB's Robot IRB660 Deep Learning for Path Optimization

The aim of this project is to optimize the time for the movement of IRB660 ABB's Robot.

**Explain more**
pic.jpg

Point A to point B can be optimized using MoveC function

# Requirements

The codebase is implemented in Python 3.7. To install the necessary requirements, run the following commands:

If you use the python shipped virtual environments:
```
python3 -m venv <your_env_name>
source your_env_name/bin/activate
pip3 install -r requirements.txt
```

If you use conda:
```
conda create <your_env_name>
conda activate your_env_name 
conda install --yes --file requirements.txt
while read requirement; do conda install --yes $requirement; done < requirements.txt
```

## Example Use Case

Palletizing - Robot Studio
pic.png

## Attributes (in Robot Studio)
1. point A
2. point B
3. point C
4. point C (as a list)
5. pGetMid
6. pSwop (as a list)
7. clk

## Workflows

Train --> Predict --> Test --> Optimize --> Execute

## Result
 
2-3 % optimize
