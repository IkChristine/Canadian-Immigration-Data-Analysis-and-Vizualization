# Canadian-Immigration-Data-Analysis-and-Vizualization
Immigration to Canada from 1980 to 2013


## Table of Contents

<div class="alert alert-block alert-info" style="margin-top: 20px">

1.  [Exploring Datasets with *pandas*](#0)<br>

1.1 [The Dataset: Immigration to Canada from 1980 to 2013](#2)<br>

Dataset Source: [International migration flows to and from selected countries - The 2015 revision](http://www.un.org/en/development/desa/population/migration/data/empirical2/migrationflows.shtml?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDV0101ENSkillsNetwork20297740-2021-01-01).

The dataset contains annual data on the flows of international immigrants as recorded by the countries of destination. The data presents both inflows and outflows according to the place of birth, citizenship or place of previous / next residence both for foreigners and nationals. The current version presents data pertaining to 45 countries.

This Analysis focuses on the Canadian immigration data.

![Data Preview](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/labs/Module%201/images/DataSnapshot.png)

The Canada Immigration dataset can be fetched from <a href="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/Canada.xlsx?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDV0101ENSkillsNetwork20297740-2021-01-01">here</a>.


1.2 [*pandas* Basics](#4) <br>
* download and import our primary Canadian Immigration dataset using *pandas*'s `read_excel()` method.
* view the top 5 rows of the dataset using the `head()` function.
* use the `info()` method to get a short summary of the dataframe.
* clean the data set to remove a few unnecessary columns. We can use *pandas* `drop()` method
* rename the columns so that they make sense. We can use `rename()` method by passing in a dictionary of old and new names
* add a 'Total' column that sums up the total immigrants by country over the entire period 1980 - 2013
* check to see how many null objects we have in the dataset


1.3 [*pandas* Intermediate: Indexing and Selection (Slicing)](#6) <br>
2\. [Visualizing Data using Matplotlib](#8) <br>
2.1 [Matplotlib: Standard Python Visualization Library](#10) <br>
3\. [Line Plots](#12)
**Let's start with a case study:**

In 2010, Haiti suffered a catastrophic magnitude 7.0 earthquake. The quake caused widespread devastation and loss of life and about three million people were affected by this natural disaster. As part of Canada's humanitarian effort, the Government of Canada stepped up its effort in accepting refugees from Haiti. We can quickly visualize this effort using a `Line` plot:

**Question:** Plot a line graph of immigration from Haiti using `df.plot()`.
We can clearly notice how number of immigrants from Haiti spiked up from 2010 as Canada stepped up its efforts to accept refugees from Haiti.
![image](https://github.com/IkChristine/Canadian-Immigration-Data-Analysis-and-Vizualization/assets/104997783/bf19c856-6b8d-4bed-ae59-fd7a587db75a)


**Question:** Let's compare the number of immigrants from India and China from 1980 to 2013.
China and India have very similar immigration trends through the years.
![image](https://github.com/IkChristine/Canadian-Immigration-Data-Analysis-and-Vizualization/assets/104997783/7c9a453b-2ab7-42d0-8367-bb7742ad050a)


**Question:** Compare the trend of top 5 countries that contributed the most to immigration to Canada.
The spike of Philippines migration to Canada in 2010 surpassed India.
![image](https://github.com/IkChristine/Canadian-Immigration-Data-Analysis-and-Vizualization/assets/104997783/63d2258d-aeec-40aa-9d85-aa95685d8b6e)






</div>

