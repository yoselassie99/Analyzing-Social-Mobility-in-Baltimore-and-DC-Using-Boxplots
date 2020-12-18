# Analyzing and Comparing Social Mobility in Baltimore and DC Through Box Plots
## Background
Part of what makes America unique is the "American Dream", which is a belief that regardless of identity, origin or social status, any dream or goal can be made a reality. This concept attracts people from around the world, as they imagine a better future for themselves and their families. While hopes of a "brighter tomorrow" still drives hundreds of thousands to America each year, the same fervant belief in the American system is no longer present within [Americans](https://www.poynter.org/reporting-editing/2020/what-is-the-american-dream-in-2020-if-there-is-one/). 

Inability in achieving social mobility within low-income communities has created great complacency, resulting in generational [poverty](https://www.nccp.org/publication/childhood-and-intergenerational-poverty/). Resources that help children achieve social mobility and high quality of life, such as strong education systems, healthcare systems and extracurricular activities, are often scarce in low income communities. In constrast, these resources are in abundance for high income children, giving them a comparative advantage in maintaining or improving their quality of life. 

Two cities heading in completely different directions are Washington, D.C and Baltimore. D.C is experiencing great economic growth, with most metrics suggesting DC is growing at a faster rate than the [United States](https://www.bestplaces.net/economy/city/district_of_columbia/washington). Baltimore, however, is experiencing low growth compared to other American cities. A lack of opportunities, coupled with failing school systems and lack of infrastructure, has made Baltimore one of the few cities to experience a declining population [size](https://apnews.com/article/8891612dc28745b6a5ae538f91812783).

Using Python, we will analyze different metrics from Baltimore and DC to determine an individual's ability to achieve social mobility. These metrics include median household income, percentage of adults who stayed in same tract, and median income among adults who stayed in same tract. 

## Business Question
What can Baltimore and Washington, DC open data sources tell us about social mobility?

## Data Source 
Data was found from the [Opportunity Atlas Database](https://www.opportunityatlas.org/).
Data on median household income, percentage of adults who stayed in same tract, and median income among adults who stayed in same tract was extracted for Baltimore and DC. Process for cleaning data is included [here](https://colab.research.google.com/drive/1eCiJZyu8E-9K_7lrFo50r6eRZxm5udtH#scrollTo=RF_ektsqQ_91). Raw Data is provided below:

Median Income:

[Baltimore](https://raw.githubusercontent.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/main/BaltimoreHouseholdIncome.csv)

[DC](https://raw.githubusercontent.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/main/DCHouseholdIncome.csv)

Income of Those Stayed:

[Baltimore](https://raw.githubusercontent.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/main/BaltimoreIncomeStay.csv)

[DC](https://raw.githubusercontent.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/main/DCHouseholdIncomeStay.csv)

Percent Stay:

[Baltimore](

[DC](https://raw.githubusercontent.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/main/DCPercentStay.csv)

## Data Visualizations (Box Plots)
Data was analyzed and converted to visualizations using Python on [Google Colaboratory](https://colab.research.google.com/drive/1eCiJZyu8E-9K_7lrFo50r6eRZxm5udtH#scrollTo=RF_ektsqQ_91).
### Baltimore vs DC Median Income
![alt_text](https://github.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/blob/main/BaltimoreMedianIncomePlot.png)
- Highest Income is $75.5K
- Lowest Income is $16.0K
- Q1 Income is $21.7K
- Q3 Income is $36.4K
- The median is $27.5K

![alt_text](https://github.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/blob/main/DCMedianIncomeBox.png)
- Highest Income is $83.5K
- Lowest Income is $19.2K
- Q1 Income is $25.6K
- Q3 Income is $40.0K
- The median is $30.3K

### Summary on Baltimore vs DC Median Income 
DC overall has greater income than Baltimore. Highest income, lowest income, Q1, Q3 and median in DC were all higher than in Baltimore. This would suggest children in DC are afforded more opportunities than children in Baltimore based on parents' income. 

### Baltimore vs DC Stayed In Commuting Zone Income
![alt_text](https://github.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/blob/main/BaltimoreIncomeStay.png)
- Maximum Income is $68.1K
- Minimum Income is $15.9K
- Q1 Income is $22.0K
- Q3 Income is $35.5K
- The median is $27.0K

![alt_text](https://github.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/blob/main/DCIncomeStay.png)
- Highest Income is $73.6K
- Lowest Income is 20.7K
- Q1 Income is $26.5K
- Q3 Income is $37.7K
- The median is $30.6K
### Summary on Baltimore vs DC Stayed in Commuting Zone Income 
Again, income of those that stayed in DC is greater than those that stayed in Baltimore. This could be because of the economic growth experienced in DC, as discussed in the background section. As a result, there are greater and more fruitful opportunities. Opportunities in Baltimore may not rival similar opportunities in other cities, which would result in Baltimore residents moving out for higher wages. 

### Baltimore vs DC Percentage Stayed 
![alt_text](https://github.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/blob/main/BaltimoreStayPercentage.png)
- Highest Percentage is 36.0%
- Lowest Percentage is 6.1%
- Q1 Percentage Stay is 18.2%
- Q3 Percentage Stay is 23.8%
- The median is 21.1%

![alt_text](https://github.com/yoselassie99/Analyzing-Social-Mobility-in-Baltimore-and-DC-Using-Boxplots/blob/main/DCStayPercentage.png)
- Highest Percentage is 37.6%
- Lowest Percentage is 5.0%
- Q1 Percentage is 17.7%
- Q3 Percentage is 26.5%
- The median is 22.6%

### Summary on Baltimore vs DC Percentage
DC and Baltimore are fairly similar in terms of percentage of residents that stay in their communiting zones as adults. The only noticeable difference between the two boxplots is the Q3 in DC is about 27% while Q3 in Baltimore is about 24%. Reasons for why a higher percentage of people may choose to stay in DC versus Baltimore is because better living conditions in DC compared to Baltimore makes staying in the city more attractive. In addition, there may be better opportunities in DC than Baltimore, further incentivizing residents to stay in the city. 

## Full Project
Codes for box plots are included [here](https://colab.research.google.com/drive/1eCiJZyu8E-9K_7lrFo50r6eRZxm5udtH#scrollTo=RF_ektsqQ_91) under  "Box Plots" in the table of contents. The link also includes step by step coding for the full project. 
