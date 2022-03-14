# DATA VISUALIZATION AND FORECASTING OF LOCAL GOVERNMENT FUND APPROPRIATION USING THE K-NEAREST NEIGHBORS REGRESSION
Jens Gabriel Jovellano1*, Ron Lara2, Jovey Ann Erepol3, Kelsey Lantano4,Ray Carlo Abacan 5 , and Joferson Bombasi 6

1 College of Computer Studies and Multimedia Arts, Far Eastern University-Alabang,
Muntinlupa City, PHILIPPINES
*Corresponding author: jensjovellano@gmail.com
 

Abstract: Government transparency embraces accountability. It is linked to and provides the enabling environment for greater accountability and is therefore presumed to operate in a continuum. The effectiveness of transparency is measured by the degree of accountability that it would provide to government personnel. The problem is, the data available from the government’s Commission on Audit website can be quite complex and confusing to the average Filipino. So, to best present the data of the government’s fund appropriations for transparency, the researchers developed a web application that uses data visualization. The best visualizations help viewers understand not only the data but also its implications. Previous research has found that 65% of the general population are visual learners, meaning they need to see information in order to retain it. Studies have also shown that the brain can process images and videos 60,000 times faster than text, making image-based communication remarkably valuable. The researchers used the general public fund data between 2016-2020 in every city of the Philippines from the Commission On Audit (COA) website to be used for data visualization and forecasting, using the K Nearest Neighbor Regression Algorithm to get an ideal output or fund in the next year by averaging the closest observations or data from the user's input with an optimal number or neighbor. This web application results in further expanding its connections towards the Filipino public and strengthening its local governments' accountability. It will not only help the local government unit to gain more benefits but also help the general public to fully deepen their understanding of government fund appropriations.

Keywords: Forecasting; K-Nearest Neighbors; Government; Transparency; Data Analysis; Data Visualization Funds; Fund Appropriations

 

1. Introduction
The way our government collects and spends money is critically important. It is not possible to ensure that government decisions are fair and efficient unless that very information is made publicly available. The government letting their actions be known to the public is called transparency, and being transparent to their constituents gives them benefits. As a concept, transparency embraces accountability. It is linked to and provides the enabling environment for greater accountability and is therefore presumed to operate in a continuum. The effectiveness of transparency is measured by the degree of accountability that it would provide to government personnel. Transparency is a matter of opening up government and governance to public scrutiny and encouraging greater citizens’ participation. (Castillo, 2020) 
According to Transparency International’s annual Corruption Perception Index (2020), Denmark is the least corrupt country in the world for the fifth year in a row. Integrity in politics is key to fighting against corruption and here Denmark takes the lead once again. The higher rank is vastly due to Denmark's high degree of press freedom, 

access to information about public expenditure, stronger standards of integrity for public officials, and an independent judicial system. (Studyindenmark, 2020). 
Transparency also helps ensure that national security professionals are held to account when transgressions arise. When security agencies are too secretive, it makes it more difficult for citizens to trust them. This reinforces a dynamic of suspicion (Juneau & Rochon, 2021). Therefore, the researchers need to collect data from governments or municipalities that have a good record of accomplishment and transparency to further improve their reputation. 
Meanwhile, government transparency is needed as it shows how fair and honest a government is. Leading with transparency helps you ensure that both the leader and its constituents’ expectations are appropriately set and satisfied. People are more likely to trust on their government and make incorrect assumptions about it when both sides communicate clearly. 
Government fund appropriations are used for a variety of uses. This includes different categories such as: health, welfare, education, natural disasters, etc. In the government fund appropriations, these different categories are shown with a percentage of the appropriation, the document shows how much is used and what it is used for. 
Moreover, government transparency is wasted if it is not used interactively with its users. With that said, according to Questica, public engagement in capital planning helps citizens feel connected to their local government. In particular, transparency about capital budgets can help citizens understand spending decisions and how taxpayer money is being spent. (Questica, 2019) 
According to Gregory J. Greben, the best visualizations help viewers understand not only the data, but also their implications. Financial data represented in both absolute and relative forms communicates more than the simple data that underpins it. (Greben & Chenok, 2013) 
Notably, research has found that 65 percent of the general population are visual learners, meaning they need to see information in order to retain it. Visuals add a component to communication that written and verbal methods do not: speed. Studies have shown that the brain can process images and videos 60,000 times faster than text, making image-based communication remarkably valuable. (SPENCER, 2018) 
Now that the importance of transparency has been established, the importance of good presentation of the said data by government transparency is also something to consider. That is why this study aims to analyze and visualize public fund appropriation data so that the public can easily and more effectively understand what happens with these public funds. 
Relatively, the researchers plan to conduct a data science study with an emphasis on visualization and public fund appropriation insights on the local government fund appropriation using the K-Nearest Neighbor Regression, to further enhance the presentation of the public fund data, and to provide insight on future fund appropriations. 

2. Literature Review 
According to Stephan G. Grimmelikhuijsen and Albert J. Meijer, comprehensibility is an important dimension of government transparency. Comprehensibility is the simplicity and clarity of the information disclosed, or how easy it is to understand for its readers, in this case, the public.
Comprehensibility is an important factor for this study, as the researchers aim to visualize fund appropriation data available from the COA website, in a way that is easy to understand for the general public. In this way, the government will improve its transparency and the public will have a better understanding of government funds, and fund appropriations. (Stephan G. Grimmelikhuijsen, 2012)
Visual design of information and data is important not only for increasing perceptibility but also for revealing the patterns within complex information, and being educative, persuasive and guiding depending on the content and objective. In this sense, incorporating data visualization works with the data of fund appropriations, and it would have a significant impact on the comprehensibility of the fund appropriation data. The graphic forms that we currently use date back many years ago. However, we see similar forms of present graphics like bar charts, column charts, doughnut charts and pie charts. (Dur, 2014).
Remarkbly, these charts will be used as tools for key decision makers and the public to see complex analysis in a visual layout, so that they can identify new patterns or grasp other underlying concepts. It will also serve as a tool for visualization of the data from the fund appropriation, namely: bar, line, and pie charts, which will be mostly used, as these three are the most common and most favored type of charts of most people. (Labs, 2019)
Data visualization is the discipline of trying to understand data by placing it in a visual context so that patterns, trends, and correlations that might not otherwise be detected can be exposed. With that said, Python offers many visualization libraries that have a lot of different features. An example of one of these said libraries is Plotly, a great tool that can provide data visualization, analytics, and statistical tools that will be useful for this study. (Tanner, 2019)

Furthermore, data visualization plays a vital role in this paper because it represents the initial phase of analytics (i.e., represents available data and it concludes what attributes and parameters are to be used to build a predictive machine), This helps the proponents to provide solutions with various approaches, In addition, data visualization also represents the "outcome". The outcome of the data gathered can be represented and compared with other data (e.g. older data of sales). As a result of comparing, it will lead to better organizational decisions. (Brush, 2020)

According to Sukumar Ganapati, Christopher Reddick, and Gabriel Puron-Cid, Governments that struggle with issues of financial sustainability and corruption will rely more on online financial transparency. Transparency increases the detection of public corruption. Contextual factors like population explain online financial transparency, while financial sustainability and corruption have moderating and negative effects. (Puron-Cid, Reddick, & Ganapati, 2019)

Meanwhile, making citizens able to monitor and evaluate public spending activities is a fundamental issue in public financial management literature. The potential positive effects of fiscal transparency are mediated by the level of democracy in the country. In detail, in democratic countries, a higher degree of disclosure of fiscal information is correlated with a higher efficiency of government spending while, in non-democratic countries, fiscal transparency does not seem to have any effect. (De Simone, Bonasia, Gaeta, & Cicatiello, 2019)

2.1 Problem Statement
Government transparency in the Philippines comes in the form of various audit reports and financial reports. To the layman, this may be hard to comprehend as these reports contain technical information and exact values.

3. Method
The type of research that the researchers will be doing is quantitative research on analyzing and computing the public appropriation fund by using it to generate the desired data visualization output.
According to Bhandari (2020), quantitative research is the process of collecting and analyzing numerical data. It can be used to find patterns and averages, make predictions, test causal relationships, and generalize results to wider populations. Quantitative research is the opposite of qualitative research, which involves collecting and analyzing non-numerical data (e.g., text, video, or audio). Quantitative research is widely used in the natural and social sciences: biology, chemistry, psychology, economics, sociology, marketing, etc.
The purpose of quantitative research is to generate knowledge and create an understanding about the social world. Quantitative research is used by social scientists, including communication researchers, to observe phenomena or occurrences affecting individuals. Social scientists are concerned with the study of people. (Allen, 2017)
Quantitative research method is performed by focusing on objective measurements and the statistical, mathematical, or numerical analysis of data collected through the means of polls, questionnaires, and surveys. This data is then generalized to explain a certain phenomenon.

The quantitative research method will be implemented in this study by analyzing the data given to the researchers, and the data collected through questionnaires and using this data as input in the K-Nearest Neighbor Regression algorithm.

3.1 Materials
Materials used in this study are various articles, and reports from Philippine researchers and news outlets. These materials are widely available for everyone with the use of a quick Google search or thru their website. One example of these news outlet websites is The Philippine Daily Inquirer, its news are reliable and factual, and has been for the majority of its time.

3.1.1 Samples
The respondents of the study are Filipino citizens, specifically the general public with knowledge in using the internet . The researchers decided to use simple random sampling as a sampling technique. Everyone was chosen entirely by chance and each member of the population had an equal chance or probability of being selected. Simple random sampling was chosen because of its simplicity and lack of bias in choosing a sample. When using a simple random sampling the researchers used the “method of a lottery “to draw numbers from a box (This was done through an online platform). In this method, the researchers gave the population and their respective numbers. The researchers then drew numbers from the box to randomly choose samples. A total of 50 random participants were selected based on the said criteria. 
The evaluators of the study were done by a group of local government officials. The researchers decided to use non probability sampling which is convenience sampling whereas the participants was chosen based on availability and willingness to take part.  

3.1.2 Site
The gathering of data involves information about data fund appropriation.  The researchers made use of the data from the government unit (Commision On Audit) which is already publicly available on their website. The researchers gathered the stated data to use it for the study and to further make an analysis and deepen the understanding towards the data public fund appropriation of the Local Government Unit. The interviews were conducted to preserve the authentic data gathered.
3.1.3 Procedures
The type of research that the proponents will be doing is quantitative research on analyzing the visualization and the forecast of the public appropriation fund by using it to generate the desired data visualization output. The quantitative research method will be implemented in this study by analyzing the data given to the proponents, and the data collected through questionnaires and using this data as input in the K-Nearest Neighbor Regression algorithm in the website project.

The system would have two interfaces made separately for the admin and the public user. Admin users have the option to login for modifying the data, while public users can only view the data or forecasted data  of the fund appropriation by visualization.

The input will be the five years' worth of public appropriation fund such as revenues and appropriations from the local government unit as raw data. The reports or the raw data will first be compiled for each type of appropriations and type of revenues or possible factors that affects the appropriations as one big data in order to avoid iteration of data cleansing on each annual reports. The data cleansing of the raw data will undergo four processes, which are the removal of duplicate or irrelevant data, fixing structural errors, identifying and removing outliers, and handling missing data. The cleansed data will be inserted to the database for data visualization and insights. 

The second process contains how the existing data will be manipulated to develop outputs and also the data visualization of the public fund appropriation data. The data from the database will first be selected by the KNN algorithm function based on the user’s choice of input to use it as the testing data. The program will now identify the distances between the predictor value and the existing values in the selected columns in the database to get the predicted value by using the Euclidean distance formula. After calculating distances, the program will now pick the nearest values with a number of K-values to calculate the mean and use it as an insight.

The third and last process contains the output of the processed data which is the visualization model that is composed of a bar chart for comparison, pie chart for proportions and a line graph for trends together with an insights of the data with the scatter plot for the regression analysis of the public fund appropriation of the local government unit.

The KNN regression algorithm will be using the following variables with their corresponding values from the raw data:
The Oi observation variable – all of the number of available observations from the database which are 2015, 2016, 2017, 2018, and 2019 annual reports with each different results in appropriations and revenues. 
The predictor variable – the type of the predictor variable will be based on the user’s selected input t to get all of the xi plot variable on each observation.
The predicted variable – the type of the predicted variable will also be based on the user’s selected input to get all of the yi plot variable on each observation.
The xi plot variable – values that will be selected based on the type of the predictor variable from the database to be used to calculate the distances on getting the similar values or the K variable.  
The yi plot variable – values that will be selected based on the type of the predicted variable from the database to be used on calculating the average value of similar K values to get the predicted variable.
The optimal K value – will be the optimal number of observations that will be included within the nearest values of the predictor variable to get the average for the optimal output.
The researchers tried to gather respondents from as much different regions as possible, the respondents from various regions of the Philippines were in total of 53 respondents.

3.2 Measurement
The proponents will use the public appropriation fund as raw data that they will get from the COA (Commision on Audit) and cleanse the data to form it as a data set. The data set will be inserted from the database and whenever the forecast insight function is called then the data from the database will now be used as the testing data for building the K-Nearest Neighbor regression model. After entering the testing data, the application will first find the optimal k-value using cross-validation with the root mean square prediction error (RMSPE) to check  how well the predictions matched the true labels. The application will now calculate the distance of the points by using the Euclidean distance formula and get the nearest values based on the number of the optimal K value. The application will now calculate the mean of the nearest k-values for presentation of the data as an insight.


Figure 1: Euclidean Distance Formula

The figure above shows the formula of the algorithm that the proponents will apply to solve the distance of the points. In the KNN algorithm, the formula will be used to get all of the distances between the predicted variable input and all of the observed variables from the existing data to get a similar value.


Figure 2: RMSPE Formula on Optimal K value

Figure 2 reveals the formula for the root mean square prediction error that the proponents will apply in order to give an optimal insight. The formula will be used for cross-validation on choosing the optimal K value. If the predictions are very close to the true values, then RMSPE will be small. If, on the other-hand, the predictions are very different from the true values, then the RMSPE will be quite large. When the proponents use cross validation, they will choose the K that gives them the smallest RMSPE.



3.3 Data Analysis
After the researchers conducted the survey, they tallied, computed, and tabulated
the results of the survey of the respondents. The results were presented using charts
and tables. The survey questionnaire is comprised of 11 questions covering the
Functionality, Usability, Reliability, Performance, and Supportability of the web
application. The researchers made use of a 5-point Likert scale for satisfaction which
indicates he following:

Legend:
● 1 – Highly Dissatisfied
● 2 – Dissatisfied
● 3 – Neutral
● 4 – Satisfied
● 5 – Highly Satisfied
Formula for Weighted Mean = ((S1*X1)...+(Sn*Xn))Total Number of Respondents
Legend
S1 – Satisfactory Rate
X1 – Score

3.3.1 Validity and Reliability

Figure 4: Getting the Accuracy Score of the Model
Figure 4 shows the process of getting the total accuracy score of the model based on the percentage score of the different predictions or outputs with the different K-values. The predictions set column are predictions computed during the iteration for the optimal K and the accuracy score column are the percentage scores also computed during the iteration. In this case, the predictions would be the Old Number in the formula and the test set would be the New Number in the formula to compare each prediction to the test set or specifically the Ytest. Each percentage score will be computed by the difference between the prediction and the test set divided by the test set value to get each of its corresponding accuracy scores. Each accuracy score will now be used to compute its average mean for the final accuracy score..

4. Results and Discussion
The researchers used visual tools like graphs and tables to present the summary of findings. The findings of the study are systematically organized based on the arrangement of the statements that were evaluated.
Presentation of Respondents
Group of Respondents
Frequency
Field Expert (Former SQL Developer in Finance Department)
1
Accountants who work/worked in a Municipality
10
General Filipino Public
42
Total
53

Figure 5 Demographic of Respondents
The researchers chose the field expert who had experience working as a developer in the finance department of the company he worked for, as well as the accountants who work/worked in a municipality, to participate in the survey because the researchers knew they are the ones who have knowledge about how Fund Appropriations work. For the general Filipino public, they were selected because the researchers knew that they are the ones that will benefit the most from the use of the web application. Most of the general Filipino public respondents are Middle Class workers, who are the working class tax payers. 
The researchers tried to gather respondents from as much different regions as possible, the respondents from various regions of the Philippines is shown below in a table.
Region
Frequency
National Capital Region
8
Region 4A - CALABARZON
17
Region 4B - MIMAROPA
2
Region 3 – Central Luzon
3
Region 6 – Western Visayas
7
Region 7 – Central Visayas
1
Region 8 - Eastern Visayas
4
Region 13 – Caraga Administrative Region
11
TOTAL
53

Figure 6 Demographic by Location of Respondents
The developed web application titled Aninaw-Tech was developed to help the general Filipino public in understanding the fund appropriations of the local government units of the Philippines. This said web application also helps those in the sector of fund appropriations with the provided insights and forecasted values. The researchers administered the surveys to 53 participants.
Responses Summary


Mean
Verbal Interpretation
Functionality
4.23
Satisfied
Usability
4.29
Satisfied
Reliability
4.32
Satisfied
Performance
4.12
Satisfied
Supportability
4.17
Satisfied

Figure 7 Summary of Responses per Portion of F.U.R.P.S.
The evaluation of the respondents is shown in the above table. The survey is divided into three (5) quality factors name Functionality, Usability, Reliability, Performance, and Supportability. The average mean for Functionality is 4.23 which has a verbal interpretation of Satisfied. The Usability factor got an average mean of 4.29 which has a verbal interpretation of Satisfied. The Reliability factor got an average mean of 4.32 which has a verbal interpretation of Satisfied. The Performance factor got an average mean of 4.12 which has a verbal interpretation of Satisfied. And lastly, the Supportability got an average mean of 4.17 which also has a verbal interpretation of Satisfied.
5. Conclusion
The use of the K-Nearest Neighbor Regression algorithm on providing insights for the fund appropriation outcomes for coming years is incorporated in the web application and is achieved.
The relationship of the factors that affect the appropriations in the K-Nearest Neighbor Regression Model relies on the data of fund appropriations that is composed of maintenance services, General Public services, etc.
The related attributes that are significant for the visualization are Data (Revenue/appropriation), Year, Region and City,
Using the K-Nearest Neighbor Regression algorithm the web application is able to achieve its objective to forecast and make insights for the decision-makers
The developed application was tested and evaluated by the expert working on the government unit/accountants.
Furthermore, after implementing the K-Nearest Neighbors Algorithm, the web application has provided various visualizations and insights for use of the general Filipino public and field experts that handles fund appropriations. Based on the results and the fund appropriation data, the researchers determined the relationship between the Revenue and Appropriations – the Revenues are always greater than the Appropriation, resulting in surplus for every year.
Based on the results of this study, this study proved that this web application can help the local government units in the regions where the web application was evaluated and tested at least, namely: 
National Capital Region
Region 3
Region 4A
Region 4B
Region 6
Region 7
Region 8
Region 13
This web application can also help to further expand its connections towards the Filipino public and strengthen its local governments accountability. It will not only help the local government unit to gain more benefits but also help the general public to fully deepen their understanding of government fund appropriations.
Also, through the use of the KNN Regression algorithm, the authorities in local government funds can use this web application to attain insights on how fund appropriations should continue in the future.
6. Acknowledgement
The researchers would like to express their deep and sincere gratitude to their thesis advisers: Dr. Ray Carlo A. Abacan, and Dr. Joferson L. Bombasi. The researchers would also like to express their heartfelt gratitude to their late thesis mentor Ms. Resty F. Aldana. The researchers are extremely grateful to be given the opportunity to carry out and present this thesis project.
The researchers are also grateful to their parents, with their never ending support, love, and sacrifices so that the researchers would successfully complete their thesis project.

References
Allen, M. (2017). The SAGE encyclopedia of communication research methods (Vols. 1-4). Thousand Oaks, CA: SAGE Publications, Inc doi: 10.4135/9781483381411 https://libguides.uta.edu/quantitative_and_qualitative_research/quant


Bhandari, P. (2020, June 12) An introduction to quantitative research. Scribbr. https://www.scribbr.com/methodology/quantitative-research/


Castillo, L. C. (2020, January 14). Transparency and Accountability in the Philippine Local Government. SpringerLink. https://link.springer.com/referenceworkentry/10.1007%2F978-3-319-31816-5_3895-1


Studyindenmark. (2020, March). Denmark is the least corrupt country in the world. https://studyindenmark.dk/news/denmark-is-the-least-corrupt-country-in-the-world


Juneau, T. & Rochon, D. (2021, January 13) Improving transparency in Canada’s national security and intelligence community. Policy Options Politiques. https://policyoptions.irpp.org/magazines/january-2021/improving-transparency-in-canadas-national-security-and-intelligence-community/

Stephan G. Grimmelikhuijsen,A. J. (2012,November 5.)Effects of Transparency on the Perceived Trustworthiness of a Government Organization Evidence from an Online Experiment.Retrieved from Oxford Academic


Greben, G. J., & Chenok, D. J. (2013). The Use of Visualization in Government. San Francisco: IBM.


Spencer, E. (2018, November 6). How to work best with the 4 different types of learners. Work Life by Atlassian. https://www.atlassian.com/blog/teamwork/how-to-work-4-different-learning-types

Questica. (2019, May 27). Budget transparency begins with data visualization. https://www.questica.com/news/budget-transparency-begins-with-data-visualization/


Dur, B. I. (2014, May). 39 | PageData Visualization and Infographicsin Visual Communication Design Education at the Age of Information. Retrieved from the arts journal: https://www.theartsjournal.org/index.php/site/article/view/460/267


Labs, B. (2019, September 14). The Top 10 Types of Data Visualization Made Simple. Retrieved from Boost Labs: https://boostlabs.com/blog/10-types-of-data-visualization-tools/


Tanner, G. (2019, January 23). Introduction to Data Visualization in Python. Retrieved from towards data science: https://towardsdatascience.com/introduction-to-data-visualization-in-python-89a54c97fbed
Brush, K., & Burns, E. (2020, February 20). data visualization. SearchBusinessAnalytics. https://searchbusinessanalytics.techtarget.com/definition/data-visualization 
Ganapati, S. and G, Puron-Cid. (2019, March 19). Public value of online financial transparency: Financial sustainability and corruption of public officials in the US state governments. emeraldinsights.
https://www.emerald.com/insight/content/doi/10.1108/IJPSM-03-2018-0073/full/html
Bonasia, M. et al. (2019, November). The effect of fiscal transparency on government spending efficiency. researchgate. 
https://www.researchgate.net/publication/337357956_The_effect_of_fiscal_transparency_on_government_spending_efficiency

Layout:
[tribunal_website_layout_design_mockup-compressed.pdf](https://github.com/pizzanoodles/thesis/files/7260988/tribunal_website_layout_design_mockup-compressed.pdf)
