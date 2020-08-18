# tr_cohort_job_matching
Exercise
_pseudocode
This program will allow the user to successfully match to a job based on individual characterisitics . Customer can only choose 5 characteristics. If 3 characteristics are chosen from set a, program will output 'Remote Developer'. Program will also provide a tally, i.e allocate a score of 20 to each characteristic chosen. Therefore if customer chooses 3 or more options from one group of characteristics, program will output the corresponding job role.

LET JobA = 'Remote Developer'
AND JobB= 'Office based Developer'

SET JOB A characteristics as 'remote' 'flexible' 'mobile' 'helpful'
Let JobA characteristics be named 'J_A'    //for the purpose of this exercise

SET JOB B characteristics as 'office based' 'react developer' 'database administrator' 
Let JobA characteristics be named 'J_B'     //for the purpose of this exercise

SET INDIVIDUAL CHARACTERISTICS1 as 'Wants to work remote' 'react experience' 'backend developer' 'AWS certified' 
Let individual characteristics 1 be named 'Ind_1'

SET INDIVIDUAL CHARACTERISTICS2 as 'looking for frontend' 'cloud experience' 'office based'
Let individual characteristics 2 be named 'Ind_2

SET customer selection to 5 //customer can only choose 5 individual characteristics

CONDITION

IF customer selects <5 characteristics
PRINT 'Five options need to be chosen'
ENDIF



FOR every characteristic customer chooses
 INCREMENT by 20
 ENDFOR
 
 IF customer selection >=60 from one group of characteristics, output role for corresponding group
 
 IF customer selects >=3 options from 'J_A'
        PRINT 'Remote Developer'
        
        
 IF customer selects >=3 options from 'J_B'
        PRINT 'Office based Developer' 
        

IF
