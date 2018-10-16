The variables : 'PassengerId', 'Ticket', 'Cabin', 'Embarked' and 'Name' did not play a part in my analysis thus i've removed them.
I filtered out rows basing on missing values in the column 'Age' since missing Age data will affect the analysis:
 * 177 is the number of non-NA/null removed observations from the column 'Age' where:
      - 125 : Not survived passengers.
      - 52 : Survived passengers.

Gender, age and social class played a major role in determining a passenger's chance to survive :

- women have a positive survival rate 75,47 %
- men have a lower survival rate 20,52 %

Social class was in favor only for women of the first and the second class:

* 96,47 % of women from 1 Class were survived
* 91,89 % of women from 2 Class were survived
* while 46,07 % of women from 3 Class were survived

Only the 'Child' and the 'Baby' Categories have highest survival rate : 

* Adult 38,10 %
* Teenager 46,93 %
* Child 52 %
* Baby 85,71 %

You will find below the survival rate for all the possible combinations ['Sex', 'Pclass', 'Category']:

* female from class 1:
   - Adult 97.4 %
   - Teenager 100.0 %
   - Child 0.0 %
* female from class 2 :
   - Adult 90.32 %
   - Teenager 100.0 %
   - Child 100.0 %
* female from class 3 :
   - Adult 41.79 %
   - Teenager 61.54 %
   - Child 38.89 %
   - Baby 100.0 %
 ***********************
* male from class 1 :
   - Adult 37.11 %
   - Teenager 100.0 %
   - Child 100.0 %
   - Baby 100.0 %
* male from class 2 :
   - Adult 6.82 %
   - Teenager 0.0 %
   - Child 100.0 %
   - Baby 100.0 %
* male from class 3 :
  - Adult 13.33 %
  - Teenager 9.52 %
  - Child 33.33 %
  - Baby 50.0 %
  *********************
 
# Women and children first
it seems it was the rule during the rescue operation.
