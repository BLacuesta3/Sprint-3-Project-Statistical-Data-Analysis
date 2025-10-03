Project Title: Sprint 3 Project/ Statistical Data Analysis 

Project Description: In this project, I will be perfroming Data Analysis in order to help the company: Megaline (hypothetical company)
decide whether the 'Surf' or 'Ultimate' predpaid plans bring in more revenue in order to help the company adjust their advertising budget.
This project includes: data cleaning/ preprocessing in order to deal with missing and duplicate values appropriately, the use of statistical
data analysis teqchniques (SDA) in order to answer questions presented by the company, an exploratory data analysis (EDA) section that
involves the use of various charts such as: histograms, bar plots and boxplots to examine and evaluate distributions in the data, and a statistical
hypothesis section in which null hypotheses that indicate whether hypotheses are rejected or not reject via the use of t-tests. 

Project Datasets:

* 'megaline_calls (2).csv'
  
* 'megaline_internet (1).csv'

* 'megaline_messages.csv'

* 'megaline_plans (1).csv'

* 'megaline_users (1).csv'

Project Tools And Libraries Used:

* Pandas

* Matplotlib

* NumPy

* Seaborn
  
* SciPy

Project Methodology: 
1) Import The Necessary Libraries

2) Read Upload The Datasets

3) Data Cleaning/ Data Preprocessing

4) Solving Project Tasks Using Statistical Data Analysis Techniques:
   
   * Project SDA Task: For each user, find: The number of calls made and minutes used per month.
     
   * Project SDA Task: For each user find: the number of text messages sent per month.
  
   * Project SDA Task : For each user find: the volume of data per month.
     
   * Project SDA Task: For each user find: the monthly revenue from each user (subtract the free package limit from the total number of calls,
     text messages, and data; multiply the result by the calling plan value; add the monthly charge depending on the calling plan).

  5) Using Exploratory Data Analysis (EDA) In Order To Study User Behavior:
      
    * Project EDA Task: Calculate some useful descriptive statistics for the aggregated and merged data, which typically reveal an overall picture
        captured by the data. Draw useful plots to help the understanding. Given that the main task is to compare the plans and decide on which one is
        more profitable, the statistics and the plots should be calculated on a per-plan basis. (Histogram and bar plot included in this task.)

    * Project EDA Task: Calculate the mean and the variable of the call duration to reason on whether users on the different plans have different behaviours
        for their calls. (Boxplot chart included in this task.)

    * Project EDA Task: Formulate conclusions on how the users behave in terms of calling. Is their behaviour different between the plans?

    * Project EDA Task: Formulate conclusions on how the users behave in terms of messaging. Is their behaviour different between the plans? 

    * Project EDA Task: Formulate conclusions on how the users tend to consume the internet traffic? Is their behaviour different between the plans? 

    * Project EDA/SDA Task: Likewise you have studied the user behaviour, statistically describe the revenue between the plans. (Histograms included in this task.) 

    6) Using t-tests In Order To Reject Or Not Reject Null Hypotheses: 

    * Project Hypothesis Task: Test the hypothesis that the average revenue from users of the Ultimate and Surf calling plans differs.
    
      Formulate the null and the alternative hypotheses, choose the statistical test, decide on the alpha value.
      
      Null Hypothesis: Average revenue collected from users of Surf and Ultimate plans are equal.

      t-test used: st.ttest_ind()
      
      Alternative Hypothesis: Average revenue collected from users of Surf and Ultimate plans are not equal.

      Hypothesis Task Result: "We reject null hypothesis".  Average revenue collected from users of Surf and Ultiamte Plans are not equal. 

    * Project Hypothesis Task: Test the hypothesis that the average revenue from users in the NY-NJ area is different from that of the users from the other regions.

      Formulate the null and the alternative hypotheses, choose the statistical test, decide on the alpha value.

      Null Hypothesis: The average revenue collected from users in NY-NJ area is equal to the average revenue collected from users of other regions.

      Alternative Hypothesis: The average revenue collected from users in the NY-NJ area is not equal to the average revenue collected from users of other regions.

      ttest used: st.ttest_ind() 

      Hypothesis Task Result: "We reject null hypothesis". The average revenue collected from users in the NY-NJ area is not equal to the average revenue collected from 
      
      users of other regions.
