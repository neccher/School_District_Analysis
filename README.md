# School_District_Analysis

## Overview
After all of our hard work in the initial analyis of school data, we were made aware that academic dishonesty had been performed while reporting the reading and math scores of Thomas High School's ninth grade class.  In order to rectify the situation and report the most accurate analysis possible, we took the ninth graders of Thomas High School out of our evaluation of school performance by replacing their scores with null values.

## Results
- How is the district summary affected?
  - Surprisingly, the district statistics seem unchanged.  
    (Before taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113428652-c8eba600-939c-11eb-9fee-48620ae7adad.png)

    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113428718-e7ea3800-939c-11eb-8bd5-2ac4cfd2cbd0.png)

    
    It is only after removing the formatting to our table when we see any alteration in the numbers.  
    (Before taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113428563-a194d900-939c-11eb-86d2-2a1700342112.png)

    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113428505-85913780-939c-11eb-9749-d2c1c39fc41c.png)
    This is because at a district level, the number of one class of students at one high school just isn't enough to change the calulations very much.  

- How is the school summary affected?
  -  As expected, the school summary would only change for Thomas High School.  However, the impact of those students' grades was far greater in the school summary compared to   the district summary.
  
    (Before taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113429675-8cb94500-939e-11eb-9cd5-0a13c751921e.png)

    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113429742-a65a8c80-939e-11eb-9056-0db2b0deb61d.png)
  
    You can see that the passing percentage for all three metrics had increased from consistent scores in the 60s to consistent scores in the 90s.
  
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - While Thomas High wasn't quite in the bottom five schools for overall performance before removing the ninth graders, it was close.  Their Overall Psasing Percentage was 65%. After removing the ninth graders, however, Overall Passing Percentage shot up to almost 91% and put Thomas High School in second place for overall performance!
  
    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113431394-4f09eb80-93a1-11eb-8b15-3a0131e1827f.png)

- Math and reading scores by grade
  - The only effect on scores by grade is now the fraudulent scores for ninth graders at Thomas High are replaced with "nan".
  
    (Math Scores by Grade)![image](https://user-images.githubusercontent.com/79211628/113431704-c0e23500-93a1-11eb-9e15-61391e32ee60.png)
  
    (Reading Scores by Grade)![image](https://user-images.githubusercontent.com/79211628/113431751-d6575f00-93a1-11eb-9c2c-43dd1cad9a8a.png)
  
- Scores by school spending
  - Again, due to formatting the table to only one decimal point, we are unable to see any effect from removing the Thomas High ninth graders.  However, after removing the formatting, we can see that there was a small impact within the $630-645 bucket.  This is expected as Thomas High School has a budget of $638 per student.
  
    (Before taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113432676-6d70e680-93a3-11eb-8976-a8689cae2388.png)

    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113432719-824d7a00-93a3-11eb-8a06-75a7832f7b81.png)
  
- Scores by school size
  - The effect continues to be minimal.  We must remove the formatting again to see any change in the data.  This time it is in the Medium bucket as Thomas High School has 1635 students.

    (Before taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113433305-90e86100-93a4-11eb-8f53-2301cf8941fb.png)

    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113433269-7910dd00-93a4-11eb-875f-a43ff3c8fda3.png)
    
- Scores by school type
  - Finally, once removing the formatting, we see that removing ninth graders at Thomas High School had a small impact on our Score by School Type analysis for Charter Schools.

    (Before taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113433679-4a473680-93a5-11eb-87f8-8e1de81f0430.png)

    (After taking out ninth graders at Thomas High)![image](https://user-images.githubusercontent.com/79211628/113433733-5c28d980-93a5-11eb-832c-6aaac2e78221.png)

