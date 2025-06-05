# Medical Appointment No shows Analysis 

### Table of contents

- [Project Aim]

- [Data sources]

- [Tools]

- [Data Cleaning]

- [Data visualization]

- [Conculsions]

### Project Aim
A person makes a doctor appointment, receives all the instructions and no-show. Who to blame?

### Data sources
Medical Appointment No shows data is taken from the kaggle 

### Tools
-Data Loading,Data cleaning, Data Visualization these all steps are performed using the tool PYTHON

### Data Cleaning
In the intial data preparation phase performed the following tasks:

1.Dropped the duplicate values that are present in the datasset of the each column. 

2. And also dropped the row of the dataset where the age of a patient was "-1".

### Data visualization

1.plotted hist graph for the whole table columns.

2.plotted histogram for Age by no show.

3.plotted barchart to know that the age and chronic diseases affect the attendance together.

4.plotted the pie chart for comparing between attendance by gender.

5.bar chart for Comparison according to age, Gender and attendance.
    -Identified that There is no correlation between age and gender affecting the show rate. The mean of gender ages are almost the same.

6.Plotted hist graph to know that reciving sms affect the attend.
    -Identified that Number of showing patients without receiving sms is greater than showing patients with receiving sms, which mean that we need to revisit our sms campaign.

### Conclusions

-Neighbourhood has a great effect on attendance or not.

-Number of showing patients from specific neighbourhood affected by receving SMS and ages.

-Age has a clear influence on the showing rate.

-Number of showing patients without reciving sms is greater than showing patients with reciving sms, which mean that we need to revisit our sms campaign.

-No clear correlation between showing and gender, chronic diseases, enrollement in the welfare program.
