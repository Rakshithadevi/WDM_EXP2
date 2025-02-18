### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### AIM: 
To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
## EMPLOYEE DATASET:

![image](https://github.com/Rakshithadevi/WDM_EXP2/assets/94165326/b81ee9be-3f19-49ed-bc69-764a3a695830)

## BANKING DATASET:

![image](https://github.com/Rakshithadevi/WDM_EXP2/assets/94165326/0666bf0f-a446-4546-ab7f-2b8e16c4b632)

## BUYING DATASET:

![image](https://github.com/Rakshithadevi/WDM_EXP2/assets/94165326/128f5fab-7a72-4fe4-bcf2-47a9cf335180)



### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
## EMPLOYEE DATASET:

![image](https://github.com/Rakshithadevi/WDM_EXP2/assets/94165326/3bd1d20c-9953-4d0a-a072-0aa1235d11b2)

## BANKING DATASET:

![image](https://github.com/Rakshithadevi/WDM_EXP2/assets/94165326/fddf07bd-d988-488d-a8c5-48a06414d9dd)

## BUYING DATASET:

![image](https://github.com/Rakshithadevi/WDM_EXP2/assets/94165326/21e75a2c-2a27-4862-8229-c6937dcb006f)



### RESULT: 
Thus the program has been successfully executed.
