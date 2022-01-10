# School_District_Analysis

## Purpose
    - Obtain clear metrics in order to have a vision of the state
    in which educational institutions are found in terms of
    percentage of approved students and budget.
    - Show through tables all the information in a summarized and clear way.
    - Extract from the analysis certain information from Thomas High School’s and review
    how does this affect the analysis.
    
## Results

#### How is the district summary affected?
    - The "Average Math Score" is affected by the fact that there are high values that are no longer considered, it decreases by 0.1 (images A-1, A-2).
    - Therefore, the "% Passing Math" column is also affected, it decreases by 0.2% (images A-1, A-2).
    - For only 0.01% the "% Passing Reading" is affected (images A-1, A-2).
    - For all the above, the "% Overall Passing" shows a decrease of 0.3%. (images A-1, A-2).
    
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/a-1_base.png) A-1 (original data)
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/a-2.png) A-2 (without 9th)

#### How is the school summary affected?
    - The values affected would be only those of Thomas High School
    - The "Average Math Score" value decreases by 0.067412 (images B-1, B-2).
    - The "Average Reading Score" increased by 0.047152 (images B-1, B-2).
    - The "% Passing Math" decreased by 26.360856% due to missing values (images B-1, B-2).
    - The "% Passing Reading" decreased by 27.64526% due to missing values (images B-1, B-2).
    - Finally the "% Overall Passing" decreases by 0.317688% (images B-1, B-2).
    - I believe that the reason the Average Reading Score increased and the "% Passing Reading"
    decreased is because the eliminated values contributed more to the passing average.
    
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/b-1_base.png) B-1 (original data)
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/b2.png) B-2 (without 9th)

#### How does replacing the ninth graders’ math and reading scores 
#### affect Thomas High School’s performance relative to the other schools?
    - If we do the calculation taking the empty values Thomas High School would be in seventh 
    place in "% Overall Passing" (image C-1).
    - However, if we do not take into account in the analysis the math and reading scores of 
    the ninth grade students go up to second place (image D-1).
    - Which to consider them or not the values strongly affects the qualification of the institute.
    
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/c-1.png) C-1
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/d-1.png) D-1

#### How does replacing the ninth-grade scores affect the following:

##### Math and reading scores by grade
    - As they are grouped by degrees simply both the math and reading values will 
    be absent (images E-1, F-1)
    
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/e-1.png) E-1
![](https://github.com/maadpeal/School_District_Analysis/blob/main/Resources/f-1.png) F-1

##### Scores by school spending
    - There is no type of affectation in this aspect since the affected values were 
    only of the qualifications.

##### Scores by school size
    - Counterintuitively, this result is not affected, probably because the 
    Thomas High School difference does not have enough weight to change the figures.
    - Another point that can affect that the variation is not reflected is due to the 
    type of format that was configured, if we had more decimals, perhaps the 
    difference could be seen.

##### Scores by school type
    - The same thing happens as in the previous point, the values are not affected.

## Summary

    - As mentioned in "How is the district summary affected?" There were four values 
    that were precisely affected by the nan values that would be: "Average Math Score", 
    "% Passing Math", "% Passing Reading" and "% Overall Passing". Some values were more 
    affected than others and that depends on how the substituted values were distributed.
