# Deep Learning homework of the team Trijó (2022)
## Team
Our team, named *Trijó*, consists of the following members:<br/>
+ Soroncz-Szabó, Flórián (J0QWCB)
+ Schäffer, Tamás (CO2WYC)
+ Frecska, Hajnalka (C1MTMR)

## Aim of the project
The primary objective is to extract a number of facial features from images of faces. For this purpose, we use some databases of facial images available online, along with some pre-trained, online available models to accelerate the learning process

### Database sources
We found 2 database sources for the project, the first one is the UTKFace database, the second one is the FairFace dataset (Face Attribute Dataset for Balanced Race, Gender, and Age).
#### UTKFace dataset
The labels of each face image is embedded in the file name, formated like [age]_[gender]_[race]_[date&time].jpg. The dataset contains over 20.000 face images.
The labels have a scale about which label what kind of values contain
+ age is an integer on a scale of 0 to 116
+ gender is 0 or 1, either its a male or a female
+ race is an integer from 0 to 4, this value defines 5 races, these are White, Black, Indian, and people from other regions like Middle East, South-America
+ date&time is given in the format of yyyymmddHHMMSSFFF, showing the date and time of each images when they were collected

https://drive.google.com/drive/folders/1HROmgviy4jUUUaCdvvrQ8PcqtNg2jn3G

#### FairFace dataset
This dataset also contains 4 different labels, these are similar to the labels of the firstly mentioned database. It includes nearly 80.000 pictures.
+ race_scores_fair is a string that shows the origin of people showed on pictures. It can have the value of White, Black, Latino_Hispanic, East, Southeast Asian, Indian and Middle Eastern
+ race_scores_fair_4 is the race of a person, it can be White, Black, Asian and Indian
+ gender_scores_fair is the sex of a person, it is either male or female
+ age_scores_fair is the age of a person showed by the dataset, is has integer values, but these are given in periods. The age may have the value of periods 0-2, 3-9, 10-19, 20-29, 30-39, 40-49, 50-59, 60-69 and 70+

https://github.com/dchen236/FairFace

### Objective as a homework
By completing this project we would like to assess how a few different hyperparameter settings and training methods influence the learning curve (time needed and achieved accuracy).
