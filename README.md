# EXPERIMENT 01: CREATION OF EMPLOYEE, WEATHER DATASET IN WEKA DATA MINING AND ANALYSIS TOOL AND PERFORM PROCESSING
## DATE: 10.02.2024 
## AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing.
## PROCEDURE: 
### CREATE DATASET:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
### Employee Table Creation:
![exp1A](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/6e53c491-4ba0-4853-aa46-1c068b3c72b6)
### Weather Table Creation:
![exp1B](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/740038c4-93c0-43cb-a7db-ff2bb86e85e4)

### PREPROCESSING DATASET:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
### EMPLOYEE:
![exp1Dadd](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/99ec740e-5539-40d0-a6fa-5d9473cf336e)
### WEATHER:
![exp1Cadd](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/00a620e1-2236-446f-be59-b12767754dec)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
### EMPLOYEE:
![exp1Dremove](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/0a217188-46d1-4039-8b4a-d0c02ce41020)
### WEATHER:
![exp1Cremove](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/b5eabc3b-b48d-4961-b716-c6d190f1ce8a)

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
### EMPLOYEE:
![exp1Dnorm](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/4d540912-a93b-43b4-89b8-7399ff7d6891)
### WEATHER:
![exp1Cnorm](https://github.com/Rithigasri/WDM_EXP1/assets/93427256/837927b4-cf94-46b7-b09a-a00537158866)
### RESULT: 
  Thus, the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
