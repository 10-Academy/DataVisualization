# Data Visualization

## What is Data Visualization

According to sas.com, Data visualization is the presentation of data in a pictorial or graphical format. It enables decision makers to see analytics presented visually, so they can grasp difficult concepts or identify new patterns. 

With interactive visualization, you can take the concept a step further by using technology to drill down into charts and graphs for more detail, interactively changing what data you see and how it’s processed.

The article attached [here](https://www.sas.com/en_us/insights/big-data/data-visualization.html) explains the **History of DataViz**, **The Current Trend of DataViz**, **How it's Used** and **How it works**

SearchBusiness explains Data Visualization as it relates to Data Science. In their Definition, Data Visualization is the practice of translating information into a visual context, such as a map or graph, to make data easier for the human brain to understand and pull insights from. The main goal of data visualization is to make it easier to identify patterns, trends and outliers in large data sets. The term is often used interchangeably with others, including information graphics, information visualization and statistical graphics.

They provide examples of Visualizations, some use cases in Business and importance. Read in details [here](https://searchbusinessanalytics.techtarget.com/definition/data-visualization).

## How will I use Data Visualization in my ML career?
How Data Vis is used by the business incl. potential linkages to interesting sample visualizations.
Data Visualization is a very important skill to have for any ML practitioner. It is a tool to communicate with stakeholders your findings and what the data entails. For example,
![dashboard](https://dreamreport.net/wp-content/uploads/Real-time-Dashboard.jpg)
the image above is a dashboard and a good use case of data visualization skill. With the dashboard, you are communicating a lot of information to Business stakeholders without saying/using any ML jargoons that sometimes stakeholders can't relate to.

Data Visualization helps uncover insights from our data. It is done before feature selection and engineering. It is to be carried out after Business Understanding and Data gathering. The output of a Data Visualization task can be a dashboard illustrating insights or a report in form of a slide deck communicating what the data entails. Data Visualization helps Data Scientist/Analyst etc build intuition about the results of the model.


## Why is it important to understand Data Visualization before starting my ML career?
As stated by Jason Brownlee (PhD), Data Visualization is an important skill in applied statistics and machine learning.
Statistics does indeed focus on quantitative descriptions and estimations of data. Data visualization provides an important suite of tools for gaining a qualitative understanding.
This can be helpful when exploring and getting to know a dataset and can help with identifying patterns, corrupt data, outliers, and much more. With a little domain knowledge, data visualizations can be used to express and demonstrate key relationships in plots and charts that are more visceral to yourself and stakeholders than measures of association or significance.

It is very important Machine Learning Engineer, Data Scientist, Analyst etc understand in detail what Data Visualization is all about, how to complete a data visualization task for any kind of dataset, how to present insights, findings and make better judgement using Data Visualization.

## How Data Visualization helps to solve a problem
Visualization helps you to see "what's happening in your data" <br>
Visualization can help you decide which analysis to use <br>
Visualization is what the business probably speaks <br>

## Examples of how you probably used Data Visualization today without realizing it
Pictures they say is lounder than words. Almost everybody has seen one or two meme images. Without saying anything you are already making inference from the picture. That is an example of Data Visualization. Now making good charts is not enough but making quality (clear, precise, neat) chart is very important. The essence is that, it must communicate something that can drive actions.

## What differentiates beginners from experts in this competency?
The use and mastery of visualization tools. An expert should know how to use Viz tools like Tableau/Power BI etc to turn Business question into actionable insights <br>
Understanding and being able to use libraries like seaborn, matplotlib etc to derive insights from data is good. Going a step further like designing an interactive dashboard, building an automatically updating dashboard is IMO an expert-like kind of thing.

## Tools/Libraries to execute data visualization tasks
1. [Matplotlib](https://matplotlib.org/stable/tutorials/index.html): a base visualization python library that makes data come to life. Simple and easy to learn and use
2. [Seaborn](https://seaborn.pydata.org/tutorial.html): a high-level python visualization library based on matplotlib. It offers additional charts and beautiful colors
3. [Plotly](https://plotly.com/python/plotly-express/): provides graphing libraries for Python, R, MATLAB, Perl, Julia, Arduino, and REST.  For python, plotly express (a module in plotly) is most popular for its high end nature, and plotly graph-objects (another module in plotly) for its vast features and customisation capabilities. Closely related, is plotly dash - a python framework well known for delivering excellent visualisation apps and dashboards. The winning point for plotly is the fact that it produces interactive chats,  something you cannot easily achieve with matplotlib and seaborn.
4. **Bokeh** is an interactive visualization library for modern web browsers. It provides elegant, concise construction of versatile graphics, and affords high-performance interactivity over large or streaming datasets. Bokeh can help anyone who would like to quickly and easily make interactive plots, dashboards, and data applications. See a live notebook [here to practice with Bokeh](https://hub.gke2.mybinder.org/user/bokeh-bokeh-notebooks-ddr2j6yu/notebooks/tutorial/00%20-%20Introduction%20and%20Setup.ipynb)
5. [d3.js](https://www.fullstackpython.com/d3-js.html): a JavaScript library for producing dynamic, interactive data visualizations in web browsers.
6. [Power BI](https://www.tutorialspoint.com/power_bi/index.htm) :: Power BI is a Data Visualization and Business Intelligence tool that converts data from different data sources to interactive dashboards and BI reports. Power BI suite provides multiple software, connector, and services - Power BI desktop, Power BI service based on Saas, and mobile Power BI apps available for different platforms. These set of services are used by business users to consume data and build BI reports. This tutorial covers all the important concepts in Power BI and provides a foundational understanding on how to use Power BI.
7. [Tableau](https://www.youtube.com/watch?v=fO7g0pnWaRA) :: Tableau is a Business Intelligence tool for visually analyzing the data. Users can create and distribute an interactive and shareable dashboard, which depict the trends, variations, and density of the data in the form of graphs and charts. Tableau can connect to files, relational and Big Data sources to acquire and process data. The software allows data blending and real-time collaboration, which makes it very unique. It is used by businesses, academic researchers, and many government organizations for visual data analysis. It is also positioned as a leader Business Intelligence and Analytics Platform in Gartner Magic Quadrant. 
8. [Altair](https://altair-viz.github.io/): a statistical visualization library for Python

## What components make up and what are key topics in Data Visualization
1. Uni-variate Analysis
2. Bi-variate Analysis
3. Multi-variate Analysis

The article [here](https://www.analyticsvidhya.com/blog/2015/05/data-visualization-resource/) explains the different kinds of chart to explore data and provides some examples
1. **Uni-variate Analysis**
  >> Univariate analysis explores each variable in a data set, separately. It looks at the range of values, as well as the central tendency of the values. It describes the pattern of response to the variable. It describes each variable on its own.
    Descriptive statistics describe and summarize data. Univariate descriptive statistics describe individual variables. [learn about uni-variate analysis here](https://www.analyticsvidhya.com/blog/2020/07/univariate-analysis-visualization-with-illustrations-in-python/) <br> In the article, a walkthrough of how to complete the univariate analysis part of a data visualization process is explained using the hello world dataset of machine learning `iris dataset`.
2. **Bi-variate Analysis**
  >> According to wikipedia, Bivariate analysis is one of the simplest forms of quantitative analysis. It involves the analysis of two variables, for the purpose of determining the empirical relationship between them. Bivariate analysis can be helpful in testing simple hypotheses of association. [The notebook attached here](https://www.kaggle.com/residentmario/bivariate-plotting-with-pandas) is a kaggle notebook that explains the art of bivariate analysis and also provides various question to solidy the understaning of what has been taught in the notebook. Do well to complete the tasks.
3. **Multi-variate Analysis**
  >> Multivariate (Multidimensional) Visualization. □ Visualization of datasets that have more than three variables.
  In this article, Dipanjan Sarkar (GDE) explains the art of effective viz for multi-dimensional data. [The Art of Effective Visualization of Multi-dimensional Data](https://towardsdatascience.com/the-art-of-effective-visualization-of-multi-dimensional-data-6c7202990c57)
  
4. **Model Visualization**
  >> Here we have charts like
  >> 1. [Clustering](https://towardsdatascience.com/cluster-analysis-create-visualize-and-interpret-customer-segments-474e55d00ebb): The most common algorithm used is k-means. k-Means starts by choosing k random centers which you can set yourself. Then, all data points are assigned to the closest center based on their Euclidean distance. Next, new centers are calculated and the data points are updated (see gif below). This process continuous until clusters do not change between iterations.
  >> ![k-means](https://miro.medium.com/max/480/1*umzqxI8Oeje8nU5EItF5dw.gif)
  >> 2. [Dendograms](https://www.data-to-viz.com/graph/dendrogram.html): A dendrogram is a network structure. It is constituted of a root node that gives birth to several nodes connected by edges or branches. The last nodes of the hierarchy are called leaves. 
  >> ![dendogram](https://www.data-to-viz.com/graph/dendrogram_files/figure-html/unnamed-chunk-3-1.png)
  >> 3. [Heatmaps](https://blog.quantinsti.com/creating-heatmap-using-python-seaborn/): A heatmap is a two-dimensional graphical representation of data where the individual values that are contained in a matrix are represented as colors. 
  >> 4. [DBSCAN](https://towardsdatascience.com/cluster-analysis-create-visualize-and-interpret-customer-segments-474e55d00ebb): (Density Based Spatial Clustering Application of Noise) which clusters data points if they are sufficiently dense. It identifies clusters and expands them by scanning neighborhoods.
  
## Charts Explanations
This section contains links that explains how various chart relate to analysis, how to interpret the charts and when to use what chart
1. [BoxPlot Explained](https://www.simplypsychology.org/boxplots.html)
2. [What is a Violinplot?](https://www.simplypsychology.org/boxplots.html)
3. [Linecharts in Detail](https://chartio.com/learn/charts/line-chart-complete-guide/)
  
## Learn More
1. [A step-by-step guide to Data Visualizations in Python](https://medium.com/codex/step-by-step-guide-to-data-visualizations-in-python-b322129a1540)
2. [Data Visualization with Python](https://www.youtube.com/watch?v=-sxwqa9dXEY)
3. [Exploring Data with python from scratch](https://www.analyticsvidhya.com/blog/2020/08/exploratory-data-analysiseda-from-scratch-in-python/)
4. [Kaggle Notebooks: Detailed exploratory data analysis with python](https://www.kaggle.com/ekami66/detailed-exploratory-data-analysis-with-python)
5. [Visual data analysis in Python](https://www.kaggle.com/kashnitsky/topic-2-visual-data-analysis-in-python)
6. [Step by Step Guide to learn Tableau](https://www.tutorialspoint.com/tableau/index.htm)
    
![ba-data_visualization_timeline-f_desktop](https://user-images.githubusercontent.com/40719064/112623839-22982180-8e2d-11eb-98d5-31eaa27b09ec.png)
![Chart_Selection](https://user-images.githubusercontent.com/40719064/112623867-2af05c80-8e2d-11eb-974b-90465d099525.jpeg)

