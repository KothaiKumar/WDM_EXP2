### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 15-02-2024
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
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
## Buying
![image](https://github.com/KothaiKumar/WDM_EXP2/assets/121215739/21604ec3-a2a8-49e3-9fe3-1b842530f1d7)
## Employee
![image](https://github.com/KothaiKumar/WDM_EXP2/assets/121215739/b3b7b5b4-a44e-4466-a3bd-c4764d218956)
## Bank
![image](https://github.com/KothaiKumar/WDM_EXP2/assets/121215739/522ce567-081d-4cdd-8e79-bef61c4742c2)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
## Buying
![image](https://github.com/KothaiKumar/WDM_EXP2/assets/121215739/2d7b34c0-5aa1-4be2-926b-f7101ec6f555)
## Employee
![image](https://github.com/KothaiKumar/WDM_EXP2/assets/121215739/4e4374fc-ec96-4f97-8a77-eaf2df11ff8b)
## Bank
![image](https://github.com/KothaiKumar/WDM_EXP2/assets/121215739/ea203eda-9291-454e-8b19-6946bd5278ee)

### RESULT: 
Thus this program has been successfully executed.
