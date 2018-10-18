# PUI2018 HW6
## Task1: Citibike Hypothesis Testing Review
### Create a pull request to provide some suggestions on my classmate Rufei Sheng(rs6431)'s Citibike project assignment. The pull request contains a CitibikeReview_ab8131.md. In this markdown profile, I provide some advice on code, statistical test method in the next step, and suggestions to improve variables.
### FKlink: https://github.com/asilayi/PUI2018_rs6431/blob/master/HW4_rs6431/CitibikeReview_ab8131.md

## Task 2
Group work with Jingtian Zhou(jz3525). He did the ANOVA test and Correlation test while I finished the Logistic Regression test.
### ANOVA
| Statistical Analyses  | IV(s) | IV type(s) | DV(s) | DV type(s) | Control Var | Control Var type | Question to be answered | H0 | alpha | link to paper |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| ANOVA  | 3, Player Level, (Professional level, Semi-profesisonal level, Non-professional level)  | Categorical  | 1, Motor Test  | Continuous  | None  | None  | Is the prognostic relevance of motor prognostic valid for identifying talents for potential players  | Players who reached APL1 had better scores in all motor test than the players who made it to the semi-professional or non-professional level  | 0.05  | [The influence of speed abilities and technical skills in early adolescence on adult success in soccer: A long-term prospective analysis using ANOVA and SEM approaches](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0182211)  |

![journal pone 0182211 g002](https://user-images.githubusercontent.com/10840545/47044980-a713ef80-d15f-11e8-820b-b85f08c26d16.PNG)

### Correlation
| Statistical Analyses  | IV(s) | IV type(s) | DV(s) | DV type(s) | Control Var | Control Var type | Question to be answered | H0 | alpha | link to paper |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Correlation  | 1, The time spent on horses with different riders' postures  | Continuous  | 1, Number of horses with neck disorders  | Discrete  | 2, Riders' rein length and Riders' heel height  | Continuous  | Is the number of horses with neck disorders larger with more time spent on low hands positions than on positions in control gourps?  | Number of horses with neck disorders in low hands positions is smaller than that in control group | 0.05  | [Human Direct Actions May Alter Animal Welfare, a Study on Horses (Equus caballus)](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0010257)  |

![journal pone 0010257 t002](https://user-images.githubusercontent.com/10840545/47058446-10f9bc80-d193-11e8-9c7c-3888e040ffab.png)

### Logistic Regression
| Statistical Analyses  | IV(s) | IV type(s) | DV(s) | DV type(s) | Control Var | Control Var type | Question to be answered | H0 | alpha | link to paper |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Logistic Regression  | 1, BMI at 7 years  | Categorical  | 1, Odds Ratio for Obesity at 13 years  | Continuous  | 2, Birth Cohort, Gender  | Categorical  | Is the incident and persistance of obesity from age 7 to 13 causing the increasing prevalence of childhood obesity in Denmark?  | The increased persistence of obesity from 7 to 13 years old increase the prevalence of obesity at age 13 years old among boys and girls   | 0.05  | [Contributions of Incidence and Persistence to the Prevalence of Childhood Obesity during the Emerging Epidemic in Denmark](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0042521)  |

![journal pone 0042521 g005](https://user-images.githubusercontent.com/10840545/47058655-f96f0380-d193-11e8-8ed0-ed6e518bb152.png)
### Task3: Reproduce the analysis of the Hard to Employ program in NY

### https://github.com/asilayi/PUI2018_ab8131/blob/master/HW6_ab8131/effectivenes%20of%20NYC%20Post-Prison%20Employment%20Programs(1).ipynb

### Task4: Tests of correlation using the scipy package with citibike data.

### https://github.com/asilayi/PUI2018_ab8131/blob/master/HW6_ab8131/citibikes_compare_distributions.ipynb
