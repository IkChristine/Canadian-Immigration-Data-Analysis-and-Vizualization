# Canadian-Immigration-Data-Analysis-and-Vizualization
Immigration to Canada from 1980 to 2013

<p>&nbsp;</p>

## Table of Contents

<div class="alert alert-block alert-info" style="margin-top: 20px">

1.  [Exploring Datasets with *pandas*](#0)<br>
1.1 [The Dataset: Immigration to Canada from 1980 to 2013](#2)<br>
1.2 [*pandas* Basics](#4) <br>
1.3 [*pandas* Intermediate: Indexing and Selection](#6) <br>
2\. [Visualizing Data using Matplotlib](#8) <br>
2.1 [Matplotlib: Standard Python Visualization Library](#10) <br>
3\. [Line Plots](#12)

</div>

<p>&nbsp;</p>

The Dataset: Immigration to Canada from 1980 to 2013

Dataset Source: International migration flows to and from selected countries - The 2015 revision
https://www.un.org/development/desa/pd/data/international-migration-flows 


The dataset contains annual data on the flows of international immigrants as recorded by the countries of destination. The data presents both inflows and outflows according to the place of birth, citizenship or place of previous / next residence both for foreigners and nationals. The current version presents data pertaining to 45 countries.

This Analysis focuses on the Canadian immigration data.

![Data Preview](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/labs/Module%201/images/DataSnapshot.png)

The Canada Immigration dataset can be fetched from <a href="https://www.un.org/development/desa/pd/sites/www.un.org.development.desa.pd/files/undesa_pd_2015_migration_flow_totals.xlsx">here</a>.

<p>&nbsp;</p>

[Exploring Datasets with *pandas*]<br>
* download and import our primary Canadian Immigration dataset using *pandas*'s `read_excel()` method.
* view the top 5 rows of the dataset using the `head()` function.
* use the `info()` method to get a short summary of the dataframe.
* clean the data set to remove a few unnecessary columns. We can use *pandas* `drop()` method
* rename the columns so that they make sense. We can use `rename()` method by passing in a dictionary of old and new names
* add a 'Total' column that sums up the total immigrants by country over the entire period 1980 - 2013
* check to see how many null objects we have in the dataset

<p>&nbsp;</p>

[Visualizing Data using Matplotlib] <br>
*  [Matplotlib: Standard Python Visualization Library] <br>
*  [Line Plots]

<p>&nbsp;</p>
**Case study:**

In 2010, Haiti suffered a catastrophic magnitude 7.0 earthquake. The quake caused widespread devastation and loss of life and about three million people were affected by this natural disaster. As part of Canada's humanitarian effort, the Government of Canada stepped up its effort in accepting refugees from Haiti. We can quickly visualize this effort using a `Line` plot:

<p>&nbsp;</p>

**Question:** Plot a line graph of immigration from Haiti using `df.plot()`.

![image](https://github.com/IkChristine/Canadian-Immigration-Data-Analysis-and-Vizualization/assets/104997783/19bb7693-da54-48f6-9cc9-a23d144826b5)


We can clearly notice how number of immigrants from Haiti spiked up from 2010 as Canada stepped up its efforts to accept refugees from Haiti.
<p>&nbsp;</p>

**Question:** Let's compare the number of immigrants from India and China from 1980 to 2013.

![image](https://github.com/IkChristine/Canadian-Immigration-Data-Analysis-and-Vizualization/assets/104997783/7c9a453b-2ab7-42d0-8367-bb7742ad050a)

China and India have very similar immigration trends through the years.
<p>&nbsp;</p>

**Question:** Compare the trend of top 5 countries that contributed the most to immigration to Canada.

![image](https://github.com/IkChristine/Canadian-Immigration-Data-Analysis-and-Vizualization/assets/104997783/63d2258d-aeec-40aa-9d85-aa95685d8b6e)

Graph shows the spike of immigration from Philippines to Canada in 2010 surpassed India.


### Reference
- United Nations. (n.d.). International migration flows. Retrieved from https://www.un.org/development/desa/pd/data/international-migration-flows
</div>

