## Table of Contents
- [General Info](#general-info)
- [Technologies](#technologies)
- [Setup](#setup)

## General Info
In this mini-project, my aim was to rework a given Spark query in order to experience a boost in performance. The following adjustments were made to the query:

- Refactor use of ```withColumns()```
- Join on ```answers_months``` instead of ```questionsDF```
- Use of left join instead of inner join    

## Technologies
Mini-project is created with: 
* Python 3.8.3
* Spark 3.0.1

## Setup
To run this mini-project, follow the steps below:

1. ```$ git clone https://github.com/BenGriffith/spark-optimization.git```
2. 
```
$ cd sample
$ spark-submit optimize.py