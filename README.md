# kickstarter_analysis
Performing analysis on Kickstarter data to determine trends
## Overview of Project
   The basis of this challenge was to determine from the Kickstarter Dataset, Outcomes of campaigns based on Launch dates and Goals.

###  Outcomes based on Launch Date
  By adding an additional criteria columns of "year" and then using the S column of "Date created Conversion", specific years were determined for each entry based on 
  outcomes of "successful, canceled, or failed."
  
#### Analysis and challenges of Project
From the newly added data of Years of the years column, a pivot table was created with fiters of "Parent Category and Years.
The challenge with the Pivot table "Theater Outcomes VS Launch" came with breaking down years into months for Row labels.  By using the reference guide
[Microsoft support](https://support.microsoft.com/en-us/office/group-or-ungroup-data-in-a-pivottable-c9d1ddd0-6580-47d1-82bc-c84a5a340725?ui=en-us&rs=en-us&ad=us),
I was able to format the rows to months.
#### Results
Conclusions that can be drawn from the Outcomes Vs Launch Date excercise are that launch dates in May procuce the most outcomes for Successful and failed results.  The trend of Succesful outcomes declines from May to September.
With Regard to the Outcomes VS Goals data and pivot table, Successful campaigns occurred most frequently in lower goal ranges, 5000 or less, and failed campaigns generally increased in higher goal ranges, 20000 to 30000.  There was also a spike in successful campaigns 35000 to 44999 range.
The limitations of the dataset may arise from outliers skewing the data to a particular direction, right or left.  In this case, to the right with he mean being greater, or to the right of the median.

![Outcomes Vs Launch](https://github.com/Danthx1138/kickstarter_analysis/blob/main/Resources/Outcome_VS_Goals.png)

![Outcomes VS Goals](


