# Machine Learning Engineer Nanodegree
## Project: Titanic Survival Exploration

### Code

The code is in the notebook file `titanic_survival_exploration.ipynb`. Additional supporting code can be found in `visuals.py`. 

### Run

```bash
jupyter notebook titanic_survival_exploration.ipynb
```

### Data

The dataset used in this project is included as `titanic_data.csv`. This dataset is provided by Udacity and contains the following attributes:

**Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

**Target Variable**
- `survival` : Survival (0 = No; 1 = Yes)

### Conclusion:

After exploratory data analysis on the titanic data, I found that `sex`, `age`, `pclass` are the most important predictors on whether someone survived. Most of the female survived, except for some of those in `pclass = 3 Lower Class`. Most of the male didn't survive, except for some of those less than 10 years old.
