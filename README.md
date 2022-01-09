# titanic

## INFO905 - Machine Learning

Sujet Kaggle : https://www.kaggle.com/c/titanic

## Description

Le but de la compétition est de pouvoir déterminer quels passagers du Titanic ont survécus.
L'application du ML se fait sur ces données :

| Variable | Definition	| Key |
| -------- |:----------:| ---:|
|survival | Survival | 0 = No, 1 = Yes |
|pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd |
|sex | Sex | |
|Age | Age | in years |
|sibsp | # of siblings / spouses aboard the Titanic | |
|parch | # of parents / children aboard the Titanic	| |
|ticket | Ticket number | |
|fare | Passenger fare | |
|cabin | Cabin number | |
|embarked |Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton |

Les données, la soumission et le notebook sont à la racine du projet.

Pour lancer notebook :
```pycon
python -m notebook
```

## Dépendances

```pycon
pip install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn six seaborn
```