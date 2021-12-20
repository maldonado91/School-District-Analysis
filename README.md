# School-District-Analysis

### 1. Overview of School District Analysis:
#### We previously summarized school and students data but later discovered we might have a case of academic dishonestly. We are going to replace some of the data with NaN values and re run the analysis. In this particular case we are focused on 9th grade data from Thomas High School and that information will be removed.

### 2. School District Analysis Results:
* How is the district summary affected?
    * There is slight drop in passing percentages across the board which is most notable in % Overall Passing. See below a before and after view:
    ![Before converting Nan's](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/district_summary_pre.PNG)
    ![After convertering Nan's](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/district_summary_post.PNG)
    
* How is the school summary affected?
   * There's also a slight drop in averages and passing percentages in the school summary but as you can see below, the difference is minimal. The average reading score is actually a bit higher after converting 9th grades scores to NaN. See below a before and after view:
    ![Before converting Nan's THS](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/ths_pre.PNG)
    ![After converting Nan's THS](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/ths_post.PNG)

* How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
   * Because of only a slight drop in average scores and percenatges, Thiomas High School has a very similar rank amonst the other schools under type Charter just like before. See below averages and percentages by school type:
    ![School types](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/school_type_summary.PNG)

* How does replacing the ninth-grade scores affect the following:
   * Math and reading scores by grade
      * Because the data remained the same for all grades except for the 9th graders at Thomas High School, the math and reading scores are the same.  
   * Scores by school spending
      * Thomas High School belongs to the $630-644 Spending Range (Per Student) so we only see a difference under this category. I left figures to the 6th decimal to display the differences as they are very very close. Only Average Reading Score is higher after removing 9th grade scores. See below a before and after view:
      ![scores_spend_pre](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/scores_byspend_pre.PNG)
      ![scores_spend_post](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/scores_byspend_post.PNG)   
   * Scores by school size
      * Similar to the school spending breakdown, Thomas High School belongs to the Medium (1000-2000) School Size so we only see a difference under this category. I left figures to the 2nd decimal to display the differences as they are very very close. Only Average Reading Score is higher after removing 9th grade scores. See below a before and after view:
      ![scores_spend_pre](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/scores_byschoolsize_pre.PNG)
      ![scores_spend_pre](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/scores_byschoolsize_post.PNG)
   * Scores by school type
      * Lastly, Thomas High School belongs to the Charter Type so we only see a difference under this category. I left figures to the 6th decimal to display the differences as they are very very close. Only Average Reading Score is higher after removing 9th grade scores. See below a before and after view:
      ![scores_spend_pre](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/scores_bytype_pre.PNG)
      ![scores_spend_pre](https://github.com/maldonado91/School-District-Analysis/blob/main/Resources/scores_bytype_post.PNG)
      
 ### 3 Summary:
#### Changing the 9th grade Thomas High School data to NaN showed very little changes in our results but we still see some slight differences.
   1. The Math scores are slightly lower
   2. The Reading scores are slightly higher
   3. Any grouping involving Thomas High School 9th graders resulted in lower scores (with the exception of Reading scores)
   4. The impact on groups not associated with Thomas High School 9th graders was none
