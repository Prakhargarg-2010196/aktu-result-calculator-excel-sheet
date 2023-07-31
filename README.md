# AKTU-RESULT 👍 👍
This is a google sheet that I created for calculating grade_point,grade_score,SGPA and CGPA

This is a general project in which I created a template for calculating your overall result for all the 8 semesters.

- [Google Sheets Link 🔗](https://docs.google.com/spreadsheets/d/1a_fN2U5p-HD5DPHgHsJjcsgswwaduWfymiYBmYKTOS4/edit?usp=sharing)
- [Github Repo Link 🔗](https://github.com/Prakhargarg-2010196/AKTU-RESULT)

## Instructions on using this sheet  ❓❓
There are 8 sheets as of now in this single google sheet one for each semester.

Each semseter sheet consists of the following structure 
## Semester Structure
![Semester Structure](https://github.com/Prakhargarg-2010196/AKTU-RESULT/assets/77922738/11698762-80c8-4186-9703-e2f4bad3a3b6)

### Important columns in this structure 
- Grade
- Grade Point
- Credits
- Grade Score
- Total Marks

## Manual Work at your end in this structure 😕
- Entering the following data
  - Internals and Externals
  - Grades
  - Credits ( You have to refer to the syllabus for this there is no way currently to adjust it or automate it 😿 )

## Functions I have created here for easing calculations 🔥
1. `GRADE_POINT_GENERATOR(grade)` : This takes the value of your grade and automatically returns the grade points.
2. `GRADE_SCORE(grade_sem,credit_sem)`: This takes the grade of that sem and credit of that sem and returns the grade score accordingly.
3. `SGPA(total_grade_score_sem,total_credits_sem)`:This takes the total grade score of the sem and total credits of that sem and returns the SGPA.

**Thus you don't have to enter the grade point,grade score and SGPA it will be automatically calculated based on other values.**

## Overall Result Structure
![Overall Result Structure](https://github.com/Prakhargarg-2010196/AKTU-RESULT/assets/77922738/5f1d809c-0af8-4a85-a684-527f35739d69)

> Note: Here in this sheet there are two SGPA columns one is manually entered and another is dynamically generated your CGPA is generated over manually entered SGPA to be accurate.But can be generated over dynamic ones also as described below.


This sheet is your overall result and hence contains all the details including the following 
### Sem-wise Details
- SGPA(statically entered)
- Total Credits
- Total Marks
- Total Grade Score
- Recalculated SGPA ( dynamically calculated)
- Charts of sgpa vs sem and total_marks vs sem 
## Yearly Details
- Total marks

## Overall 
- CGPA

## Manual Work at your end in this structure  😕
- SGPA
## Function for your Ease 🔥
- `CGPA(sgpa_sem1, credit_sem1, sgpa_sem2, credit_sem2, sgpa_sem3, credit_sem3, sgpa_sem4, credit_sem4, sgpa_sem5, credit_sem5, sgpa_sem6, credit_sem6, sgpa_sem7, credit_sem7, sgpa_sem8, credit_sem8, range_cells_credits)` 
- The above function takes the semester wise sgpa and credits and then gives back the cgpa


## References 
- [Grading and Calculations AKTU 🔗](https://aktu.ac.in/pdf/about-us/B.%20Tech.%20Ordinance_2016-17.pdf)

