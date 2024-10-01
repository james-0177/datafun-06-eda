# datafun-06-eda

Project 6 will explore creating a custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn and other popular data analytics tools.

## Create and Activate Project Virtual Environment

```shell
py -m venv .venv
.venv\Scripts\Activate
py -m pip install -r "requirements.txt"
```

## Freeze Requirements

```shell
py -m pip freeze > requirements.txt
```

## Git Add / Commit / Push 

```shell
git add .
git commit -m "create Project 6 repo, .gitignore, .venv, and README"
git push -u origin main
```
## Install external dependencies

```shell
py -m pip install -r requirements.txt
```

## Specification

This project was built to the following specification:

- [datafun-06-spec](https://github.com/denisecase/datafun-06-spec)

## Dataset

Project 6 will make use of the flights.csv dataset obtained from the seaborn library located at the following url:  https://github.com/mwaskom/seaborn-data/blob/master/flights.csv. This csv file has been copied into the Project 6 repository. The dataset contains information of flights between 1949 and 1960 and includes the year, month, and number of passengers.