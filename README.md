Online Learning Dropout Pattern Analysis





Overview

This project is about understanding how students drop out from online courses. 
In many online platforms, lot of students join the course but many of them don’t complete it. 
The main idea was not to build any prediction model or advanced AI,
but to use simple statistics and visualization to see patterns. 




Objectives
To divide students into early, mid and late dropouts
To compare engagement level between these groups
To check relation between activity data and dropout timing








Dataset

I used a synthetic dataset for this project. Real student data is difficult to get and also has privacy issues, so generating fake but realistic data was safer.
1.The dataset contains things like:
2.Course duration
3.Last day student was active
4.Number of assignments submitted
5.Total video watch time
6.Average quiz score



Tools and Libraries: Google Colab, NumPy, Pandas, Matplotlib, Seaborn, Gradio (for simple UI)

Visualizations Used:

To understand the data better, I used multiple visualizations:

Bar plots to see dropout count
Box plots to compare engagement between groups
Violin plots to understand distribution
Scatter plots to see relation between engagement and dropout ratio
Correlation heatmap for numeric relationships
These plots made it easier to see patterns instead of just numbers.





Results and Observations

From the analysis, few important things were observed:
Many students drop out very early in the course
Students who stay longer usually watch more videos and submit more assignments
Quiz score alone does not explain dropout clearly
Engagement seems more important than performance


hii



UI (Gradio)
A simple Gradio based UI was added so that the analysis can be explored interactively.
Using the UI, user can:
Select dropout phase
Choose different type of plots
View sample data
The UI is kept very simple and only used for visualization, not logic.

Author
Shubh Raj
