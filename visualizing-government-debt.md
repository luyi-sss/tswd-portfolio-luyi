| [home page](https://luyi-sss.github.io/tswd-portfolio-luyi/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing-government-debt
This dataset shows the debt-to-GDP ratio of countries between 1995 and 2019. I think there are 3 key attributes that need to be identified clearly on charts: Country, Ratio, and the change or the range of ratios within the period. 3 different data visualization ways are used to demonstrate the same dataset of the general debt from OECD.(https://data.oecd.org/)

The bar chart demonstrates the ratio of different countries:  
    The use of gray and other colors perfectly differentiates the ratios of countries and the chart tells users to focus on the ratio of Japan, Italy, the United States, France, Canada, the average ratio, and Germany.
    The bar chart makes it easy for users to read values and make comparisons. The chart is in ascending order, which is convenient for users to find maximum(Japan), minimum values(Estonia), and the average ratio.   
    The interactive way of showing the specific values of each bar is fascinating. When moving my mouse around the chart, I can navigate to different debt-to-GDP values.
    The bar chart cannot show the trend or the change in time. It only shows the data of 2021.

The grid line chart clearly shows the change in the ratio in the time:  
    We can clearly identify whether there is an upward or downward trend: Norway, Slovenia, Iceland, and Korea have the steepest debt ratio change.  
    Not easy for users to read values and make comparisons: each country has an individual chart and the starting point for data collection varies, which makes grid line charts difficult to compare data directly through charts. So I added some data labels trying to give users a data-based sense of how the ratio changed. However, the country's acronyms could be a barrier for users who are not familiar with them.
    It is easy to lose focus as the grid line charts are overdone(there are too many charts and too many countries).
  
Since the line chart shows the change in the ratio, the scatter plot provides information about the range of the debt ratio of each country from 1995 to 2021.   

What I think when designing the scatter plot:  
1. The shape is a preattentive attribute for users and I want the range of debt ratios of different countries to be my emphasis, so I choose to draw a scatter plot.
2. To better emphasize the positions of each point in the scatterplot, I chose gray as the background color to make the dots more prominent. I also chose gray for elements like the x-axis, the y-axis, and the chart title. I represented each point in purple as I think purple is clear enough to show the data. Sequential colors are good for illustrating counts. By changing the intensity of the color, it is clear to see the duration for which each country maintains a particular debt ratio. For example, the debt ratio of Italy mainly clusters within the range of 100-160. After using purple as the main color for the chart, I also used purple for the footer. This increases chart readability and helps limit colors as best as I can.
3. When deciding the dot style, I chose a square shape as it is easy to make comparisons across different countries. The square dots stacked together resemble bars in bar charts, which also provide a clear view of the maximum, minimum, and range of the debt ratio.
4. Plus, I took off the grid lines to increase the clarity and remove redundancy.
5. I played with the bump notes a little bit trying to highlight the maximum and minimum but it seems that Flourish doesn't work. 

Cons that I found when designing the scatter plot:
1. Cannot see the trend of the ratio of each country;
2. Not easy to read specific values when dots are overlapping;

## The bar chart of the Debt-to-GDP ratio:
<iframe src="https://data.oecd.org/chart/7b90" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7b90" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2022</a></iframe>

## The grid line chart of the Debt-to-GDP ratio:
<div class="flourish-embed flourish-chart" data-src="visualisation/14963280"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## The scatter plot of the Debt-to-GDP ratio:
<div class="flourish-embed flourish-scatter" data-src="visualisation/14963473"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## The scatter plot tableau ver.(waiting to be updated later):


