Instructions

**What automated approaches can you use?**

A Python script that cleans the data is the best appraoch to optimize the cleaning process. To do so I have created some funtions that will check for quality and in some cases when specific conditions aren't met, remove rows.
I have prepared some simple funtions that could help meet this purpose.

https://github.com/ehpower/code-20240501-EnriqueHidalgoPower/blob/main/Vamstar%20Task.ipynb
 
**What manual tasks would you perform?**

Manual task doesn't help with scalability. It is better to spend more time preparing a cleaning script that covers most possible scenarios, this will ensure that no matter the  number of rows the tables the data will be clean.

**How would you improve this process long term and how would you build your roadmap?**

I am a firm believer in quality controls. The reason being, that data is helpful to make informed decisions as long as it is reliable, thus its crucial to guarantee the quality of the date we are working with. In past working experiences I implemented quality controls that would interrupt the script and identify the error, this resulted in a more accurate reflection of reality thrhough the defined KPIs

**Would you change anything if you would need to scale this process from a few SKU's to hundreds and thousands.**

As i mention before, scalability and manual tasks are antonyms. Python is a very powerful language for data cleaning and with the correct use of certain libraries likes pandas, numpy... The volume of data does not affect the quality of the data itself. 

In this case, the sample data was small, and the cleaning process resulted in the removal of 1 row of the data set, however, the functions created would be helpful when scaling up the size of data.
