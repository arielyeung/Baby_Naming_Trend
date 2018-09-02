# Baby Naming Trend

## Introduction
Ever wonder how many people in the US share the same name as you? The naming trend data from Social Security application might be a way to find out the answer. The data records the number of babies born with a particular name for each year and each state starting from 1910 and is available on Data.gov. Only popular names (names with at least 5 babies born in the same year and same state) are included in the dataset.

The project is inspired by this dataset. I would like to look at what might affect how parents in the US name their babies and some recent naming trends through visualization.


One of the factors that I explored is celebrity influence. The naming trend of the name Kobe suggests that the NBA star Kobe Bryant does influence people's decision in choosing a baby name. 

<div>
    <a href="https://plot.ly/~arielyeung/237/?share_key=1Lp9PMtcdaR8ALtkX4n6LV" target="_blank" title="kobe_trend" style="display: block; text-align: center;"><img src="https://plot.ly/~arielyeung/237.png?share_key=1Lp9PMtcdaR8ALtkX4n6LV" alt="kobe_trend" style="max-width: 100%;width: 600px;"  width="1000" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>

<div>
    <a href="https://plot.ly/~arielyeung/245/?share_key=nj5NX4SvybJOL740FeXM7G" target="_blank" title="kobe_trend1" style="display: block; text-align: center;"><img src="https://plot.ly/~arielyeung/245.png?share_key=nj5NX4SvybJOL740FeXM7G" alt="kobe_trend1" style="max-width: 100%;width: 600px;"  width="600" onerror="this.onerror=null;this.src='https://plot.ly/404.png';" /></a>
</div>


I also looked at what are the most frequently used name in the past decades. From the wordcloud, Sophia and Emma are the most popular girls' name.

![](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/female_recent_wordcloud.png)

For boys, we have Mason and Noah.
![](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/male_recent_wordcloud.png)


For the rest of the project I also explored the naming trend and geographic difference of some celebrities' name, as well as some recent popular names.


## Future Research Direction
It would be interesting to gather some data from social media such as celebrities' no. of Facebook posts/ likes or no. of tweets/ followers over time and look at how that correlates to naming trend.


## Index of Repository
[Analysis](https://nbviewer.jupyter.org/github/arielyeung/Baby_Naming_Trend/blob/master/Analysis.ipynb)<br> *Codes of my analysis, including interactive plots showing naming trend over time and regional difference*


|Data|
|---|
|[Name_by_state](https://github.com/arielyeung/Baby_Naming_Trend/tree/master/Data/Name_by_state)<br>*The naming trend dataset from Social Security application*|
|[Birth_data](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Data/Birth_data.csv)<br>*The number of babies born each year*|
|[StateReadMe](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Data/StateReadMe.pdf)<br>*Data sources and variable definitions for Social Security application data*|

|Visualization|
|---|
|[all_birth_popular_name_trend](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/all_birth_popular_name_trend.png)<br>*Trend of the total no. of babies born and no. of babies with popular names from 1910-2016*|
|[birth_popular_name_trend](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/birth_popular_name_trend.png)<br>*Trend of the total no. of babies born and no. of babies with popular names from 1936-2016*|
|[unpopular_trend](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/unpopular_trend.png)<br>*Trend of the no. of babies born with unpopular names*|
|[birth_unique_name_trend](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/birth_unique_name_trend.png)<br>*Trend of the total no. of babies born and no. of unique names used*|
|[celebrity_(name)_trend](https://github.com/arielyeung/Baby_Naming_Trend/tree/master/Visualization)<br>*Naming Trend of (name) and how it correlates with celebrity's career*|
|[celebrity_(name)_map](https://github.com/arielyeung/Baby_Naming_Trend/tree/master/Visualization)<br>*% of babies with celebrity name by state*|
|[female_recent_wordcloud](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/female_recent_wordcloud.png)<br>*Wordcloud showing the most popular baby girl name in the past decade*|
|[male_recent_wordcloud](https://github.com/arielyeung/Baby_Naming_Trend/blob/master/Visualization/male_recent_wordcloud.png)<br>*Wordcloud showing the most popular baby boy name in the past decade*|
|[recent_(name)_trend](https://github.com/arielyeung/Baby_Naming_Trend/tree/master/Visualization)<br>*Naming Trend of (name)*|
|[recent_(name)_map](https://github.com/arielyeung/Baby_Naming_Trend/tree/master/Visualization)<br>*% of babies with (name) by state*|
