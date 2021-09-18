# School_District_Analysis


## Project Overview

The purpose of this project is that the school board has found evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and to repeat the complete school district analysis and check how the changes have affected the overall analysis.

## Results 

After replacing the math and reading scores for Thomas High School with NaNs below are our findings which we can conclude for our analysis :

 * **How is the district summary affected?**
 
    Original Analysis :
    
    <img width="950" alt="10" src="https://user-images.githubusercontent.com/88418201/133865747-c52ae73c-e693-4566-b29e-b0f6e70e32e4.png">
    
    Adjusted Analysis :
    
    <img width="950" alt="10" src="https://user-images.githubusercontent.com/88418201/133865783-b5c0ab7f-6038-4a39-bfd6-804877ef2f03.png">
 
    *  The Average Math Score dropped to 78.9
    *  The Average Reading Score remained same as 81.9
    *  The % Passing Math dropped to 74.8%
    *  The % Passing Reading dropped to 85.7%
    *  The % Overall Passing dropped to 64.9% 
 
* **How is the school summary affected?**

    Original Analysis :
    
    <img width="950" alt="20" src="https://user-images.githubusercontent.com/88418201/133866011-7a035e63-db89-4f5a-a429-1e31393201b8.png">
    
    Adjusted Analysis :
    
    <img width="950" alt="20" src="https://user-images.githubusercontent.com/88418201/133866119-e7be56f9-5994-4d40-b2cb-dbf3b47042dc.png">

    *  The per school summary was same for all the other 14 schools except for Thomas High School :
        *  The Average Math Score dropped from 83.41 to 83.35
        *  The Average Reading Score increased from 83.84 to 83.89
        *  The % Passing Math dropped from 93.2% to 66.9%
        *  The % Passing Reading dropped from 97.3% to 69.6%
        *  The % Overall Passing dropped from 90.9% to 65.1%
    
        <img width="950" alt="Screen Shot 2021-09-17 at 3 32 12 PM" src="https://user-images.githubusercontent.com/88418201/133860493-683937bf-0af2-4816-bfd5-efac281f9cd3.png">
    
* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

    *  The overall passing percentages of Thomas High School decreased by around 0.31% (from 90.94% to 90.63%)
    *  The average scores of Thomas High School for math and reading increased by around 0.06
    * **School rankings are unchanged**. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.
    *  Bottom five schools remain unchanged.
    
    <img width="950" alt="re2" src="https://user-images.githubusercontent.com/88418201/133867315-a66f4033-aec1-4765-a008-793f213e4c0c.png">
    
*  **How does replacing the ninth-grade scores affect the following :**

    *  **Math and reading scores by grade -**
    
        *  Math and reading scores by grade remained the same for all the other 14 schools.
        *  Thomas High School had no data to report for 9th grade math and reading scores.

            Math Scores by grade                                                    Reading Scores by grade
<img width="321" alt="math" src="https://user-images.githubusercontent.com/88418201/133862568-7a563b51-0879-4a65-8511-c54e848d6ab3.png">        <img width="312" alt="reading" src="https://user-images.githubusercontent.com/88418201/133862615-cc2ee6c9-d6af-4e22-8487-d5c8d4e7ec88.png">

   * **Scores by school spending -**
    
       Original Analysis :
       
       <img width="700" alt="s1" src="https://user-images.githubusercontent.com/88418201/133867497-6a240e90-1216-4491-b3e0-f4bd90f733bb.png">

        Adjusted Analysis :
        
       <img width="700" alt="s2" src="https://user-images.githubusercontent.com/88418201/133867501-79e05366-da9e-4d44-b09c-135b33410cf6.png">
       
       * As Thomas High School falls in the $630-$644/student spending range, we can see that there was a very little spending impact by changing the 9th grade scores to NaN.
       
   * **Scores by school size -**
        
        Original Analysis :
        
        <img width="700" alt="c1" src="https://user-images.githubusercontent.com/88418201/133867627-ba73b988-f289-4331-b009-c440bd2fb007.png">

        Adjusted Analysis :
        
        <img width="700" alt="c2" src="https://user-images.githubusercontent.com/88418201/133867633-d246cde2-059a-4da0-939b-1208e815d285.png">

        * As Thomas High School falls under the Medium sized school, we can infer from above that there was a little impact on school size by changing the 9th grade scores to NaN.
        
* **Scores by school type -**
        
    Original Analysis :
    
    <img width="700" alt="k1" src="https://user-images.githubusercontent.com/88418201/133867771-121caa22-442f-46f7-be0a-a57e705faf35.png">
    
    Adjusted Analysis :

    <img width="700" alt="k2" src="https://user-images.githubusercontent.com/88418201/133867772-5ccadd00-872e-4148-9074-5fdc3462f08f.png">
    
    * As Thomas High School is a Charter type school, we can infer that there was a very little impact on school type by changing the 9th grade scores to NaN..
    
## Summary

The four changes which we can derive from the updated school district analysis after replacing the Math and Reading scores to NaNs for Thomas High School are :

*  The Overall Passing Percentage fell from about 91% to 65%.
*  Thomas High School's ranking dropped from 2nd to 8th position in the district of 15 schools.
*  Data at the grade level for math and reading will now be shown as "NaN" in reports for the 9th grade students at Thomas High School.
*  Replacing the math and reading scores to NaN did not impact the ranking for the bottom five schools among all the 15 schools.


