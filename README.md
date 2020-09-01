[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/prabhupavitra/Data-Visualization-with-Python/blob/master/)

# Data Visualization with Python

### Significance of Data Visualization

Data Visualization is one of the most important stages in a data science project. 
It involves producing pictorial representations that convey relationships among the represented data. This is achieved through the use of a systematic mapping between graphic marks and data values in the creation of the visualization. Although the key objective in data visualization is to accurately convey the data, aesthetics play a vital role too. 
A good visualization not only helps us in discerning outliers, identifying patterns and trends but also transforms  complicated datasets into a clear and concise summary,thus improving readability and understanding.

According to Tableau, "Data Visualization" is one of the most useful professional skills to develop. The better you can convey your points visually, the better you can leverage that information.

### What comes before Data Visualization?

The first step of any data visualization process starts at discovering data. Data can be either imported as a flat file(csv/txt) or using data APIs. 
Once the data is available in raw format, the next step generally includes data cleaning and transformation. The subsequent steps include preparing data for analysis and visualization followed by the visualization itself. 
Preparing the data in turn includes several stages from identifying the data table, having appropriate headers, handling missing values, appropriate aggregation and summaries and adjusting the data layout for a optimal code for the design of the visualization in question.

## Key Terms to know

### Coordinate System
In geometry, a coordinate system is a system that uses one or more numbers, or coordinates, to uniquely determine the position of the points or other geometric elements on a manifold such as Euclidean space. 

Common examples include Cartesian coordinate system, Polar coordinate system, Geographic Coordinate Systems and so on.

### Which charts can be used for Visualizing Amounts

Most commonly used visualizations to compare amounts include:

1. Bar Charts
2. Diverging Bar Charts    
3. Stacked Bar Charts
4. Grouped Bar Charts (also called Clustered Bar Charts)
5. Animated Bar Charts
6. Dot Plots (also called Cleveland Dot Charts)
7. Bubble Charts
8. Heatmaps
9.  Waterfall Charts
10. Polar Area Charts (also called Coxcomb Charts)
11. Dumbbell Charts

### Which charts can be used for Visualizing Distributions

Most commonly used plots used for visualizing distributions include:

1. Histogram
2. Density Plot
3. Empirical cumulative distribution function
4. Boxplot
5. Violin Plot
6. Strip Chart
7. Sina Plot
8. Ridgeline Plot
9. Quantile–quantile plot

## Comparison

### Flat files vs Data API
  Flat files refer to the csv files or the delimited text files. Flat files are the universal mechanism for moving data from one database or system to another.
  On the contrary, an API is, ideally, a single consistent representation of a set of resources that allows two applications to talk to each other. 
  Examples of data api includes quandl,yahoo finance api, Eikon, Bloomberg, Haver and so on..

### Unimodal vs Bimodal vs Multimodal Data 
 The mode of a set of observations is the most commonly occurring value. A distribution with a single mode is said to be unimodal. A distribution with more than one mode is said to be bimodal, trimodal, etc., or in general, multimodal.
    The statistics that are estimated using the data is dependent on the mode of the data. Therefore a useful step before analyzing a dataset is to know if the data is unimodal/bimodal/multimodal. 
    
### Grouping vs Faceting
Grouping allows you to plot multiple variables in a single graph, using visual characteristics such as color, shape, and size.
In faceting, a graph consists of several separate plots or small multiples, one for each level of a third variable, or combination of variables

### Visualizing amounts vs Distributions
Although, both can be used to visualize numeric data; the purpose is a lot different.
  The purpose of visualizing amounts is to compare magnitude of discrete numeric data over time or any other categorical variable. Bar plots and Line plots are excellent ways to visualize amounts. The length of the bar is proportional to the magnitude of the discrete numeric variable.
  
### Visualizing Single Distribution vs Visualizing Multiple Distributions
When visualizing a single distribution our purpose is to see how a single variable is spread. One can use this plot when visualizing a single variable. Histograms and density plots are a popular choice for visualizing single distribution.

On the contrary, our intention to visualize multiple distributions in a single plot arises in various situations as discussed. For example, one might just be interested in comparing data spread of a single variable at various times for comparable data (Example: Price of precious metals); One may be curious about outliers or the density of the data points around a specified value; one might also want to compare multiple variables in a single dataset(Example: Salary distribution of male/female employees); One might be interested to know which data distribution is more volatile than the other; and so on..
The plots used in these scenarios depends on the number of distributions involved. The intention of the plot is to provide clarity on the purpose of the plot. Histograms and density plots are used when the number of distributions are less. The plots used to visualize multiple distributions includes, but not limited to, box plots, violin plot, strip chart, sina plots, ridgeline plots, boxen plots.
  
## Charts Glossary

### Bar Charts

A simple way to visualize the quantitative data of a categorical variable is the bar chart. The height ofthe bar is proportional to the quantity we want to visualize. They can be used for displaying data that are classified as nominal data/ordinal data.

They are one of the most commonly used types of plots because they are simple to create and very easy to interpret. They are also a flexible chart type and there are several variations of the standard bar chart.

Different types of bar charts:
- Horizontal bar charts
- Grouped or Component charts
- Stacked bar charts
- Diverging bar charts
- Animated bar charts

### Dot Plots

Dot plots are one of the simplest way to visualize single numerical variable with a 
modest number of observations. They are a great alternative to the bar chart and the power of these plots becomes evident on refining and they can easily communicate important aspects of your data to viewers. 

### Bubble Plot

A bubble chart uses areas of circle to represent the quantity of a numeric variable. It is a preferred when we want to represent relationship between two or more numeric variables.

### Heatmap

A heatmap depicts values for a main variable of interest across two axis variables as a grid and uses color coding to represent the quantity of values.

### Histogram

One of the simplest ways to show data spread is Histogram. To construct a histogram from a continuous variable you first need to split the data into intervals, called bins. Depending on the data distribution and the purpose of visualization, an appropriate bin width is chosen. Although software chooses a default bin width, it is vital to understand data-based binning techniques used in estimating bin width. 

### Kernel Density Plots

Kernel Density plots are a popular choice for visualizing single as well as multiple distributions because it creates a smooth curve on a given set of data. The smoothness of the curve is controlled by a bandwidth parameter that is analogous to the histogram bin width.

### Empirical cumulative distribution function

An Empirical cumulative distribution function is an estimator of the Cumulative Distribution Function. The ECDF allows you to plot a feature of your data in order from least to greatest and see the whole feature as if is distributed across the data set. It has some useful properties such as being consistent and having a known confidence band. Best of all, it's non-parametric so it will work with pretty much any distribution.

### Boxplot

A box and whisker plot—also called a box plot—displays the five-number summary of a set of data. The five-number summary includes “minimum”, first quartile (Q1), median, third quartile (Q3), and “maximum”. Box plots are useful for identifying outliers and for comparing distributions. 

### Violin Plot

A variant of the boxplot is the violin plot. It allows you to visualize the distribution of the data and its probability density. Box Plots are limited in their display of the data, as their visual simplicity tends to hide significant details about how values in the data are distributed(For instance, its not possible to know if data is bimodal or multimodal). With Violin plots, it is easy to visualize overall data density as they display the density for all data points. 

Other variations of box plots include vase plots, bean plots. The best source of information I came across regarding this topic include a paper by Hadley Wickham and Lisa Stryjewski titled 40 years of boxplots and another from Jerry L. Hintze and Ray D. Nelson titled Violin Plots: A Box Plot-Density Trace Synergism.

### Strip Chart

Stripchart produces a one dimensional scatter plot and are a good alternative to boxplots when sample sizes are small.

### Sina Plot

SinaPlot is inspired by the strip chart and the violin plot and operates by letting the normalized density of points restrict the jitter along the x-axis. The plot displays the same contour as a violin plot but resembles a simple strip chart for a small number of data points. 

### Ridgeline Plot

Ridgeline plots are partially overlapping line plots and are a useful tool for visualizing patterns/trends in distributions over time or space. They can be represented using histograms or density plots, all aligned to the same horizontal scale and presented with a slight overlap.

### Quantile-Quantile Plot

The quantile-quantile (q-q) plot is a graphical technique for determining if two data sets come from populations with a common distribution. In general, the basic idea is to compute the theoretically expected value for each data point based on the distribution in question. If the data indeed follow the assumed distribution, then the points on the q-q plot will fall approximately on a straight line.

## References 

Wes McKinney. Python for Data Analysis, 2nd Edition. 2017

Yves Hilpisch. Python for Finance, 2nd Edition. 2018
