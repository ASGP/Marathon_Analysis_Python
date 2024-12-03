# Ultra-Marathon Analysis
## Overview
This project analyzes ultra-marathon data from a dataset spanning 2010 to 2022. Using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and SciPy, the notebook provides insights into trends and patterns in ultra-marathon events, focusing on aspects like gender distribution, race distances, and athlete performance.

## Key Features
Exploratory Data Analysis (EDA):

## Initial exploration of the dataset using methods like .head(), .shape, and .describe() to understand its structure and key statistics.
Visualizations:

#### Gender Counts
| Athlete Gender | Count  |
|----------------|--------|
| M (Male)       | 47836  |
| F (Female)     | 24666  |

#### Speed in 50km and 50miles of Females and Males
| Event Distance/Length | Athlete Gender | Athlete Average Speed |
|------------------------|----------------|------------------------|
| 50km                  | F              | 6.989000              |
| 50km                  | M              | 7.654585              |
| 80.467km              | F              | 6.819738              |
| 80.467km              | M              | 7.261080              |

#### Athlete Average Speed by Race Season

| Race Season | Mean Athlete Speed | Count |
|-------------|--------------------|-------|
| Winter      | 7.535532           | 10713 |
| Spring      | 7.469398           | 31306 |
| Fall        | 7.251592           | 15318 |
| Summer      | 7.069892           | 15165 |

#### Athlete Performance by Race Season

| Race Season | Athlete Performance (Time)       |
|-------------|----------------------------------|
| Spring      | 0 days 07:56:48.368044464h       |
| Fall        | 0 days 08:07:27.271967619h       |
| Winter      | 0 days 08:23:34.252123588h       |
| Summer      | 0 days 08:43:50.988262446h       |


## Visualizations
Some visualizations generated in this project include:

* Gender Distribution:
A pie chart visualizing male and female athlete proportions.
![image](https://github.com/user-attachments/assets/d2b61a85-59f0-4ecc-a243-a16d0012734a)

* Race Distance Distribution:
Histograms showing the frequency of races for 50mi and 50km.
![image](https://github.com/user-attachments/assets/17f2cd3c-5d77-4fb4-975e-041279ff13c1)

* Athlete Speed Comparison:
KDE plots comparing speeds across different race categories
![image](https://github.com/user-attachments/assets/272cbb60-6795-4b08-8816-6fa3cc556c70)

* Gender vs Average Speed
  ![image](https://github.com/user-attachments/assets/06368523-f1e2-4942-9058-2b47429be5d9)

* Athletes Outside of USA
  ![image](https://github.com/user-attachments/assets/2d301b9b-c452-440a-8d76-f7bc2e378282)




