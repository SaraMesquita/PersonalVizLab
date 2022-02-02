# PersonalVizLab - a place to experiment

Welcome to my personal data visualization lab, where I run my dataviz experiments in (mostly) Python.



### (1) Funnel plot showing antibiotic weight in total consumption units per hsopital

<hr />

This funnel plot (shown below) is used to compare the proportion of antibiotics in the total medication, over a year, for each hospital in Portugal. It takes into consideration that smaller hospitals (that serve less people) are more vulnerable to the role of chance, and therefore tend to have more extreme results. The funnel-shaped curves are the 95% and 99.9% quantile curves under the assumption that proportions are sampled from a binomial distribution for which the probability of "success" (consume antibiotic) equals the hospital average consumption. This type of graphic is extensively used when examining multiple health authorities or institutions, since it permits the identification of outliers without creating spurious league tables.

![image](https://user-images.githubusercontent.com/24231383/151883792-7dca2be9-1f42-4e7f-bc8c-6c3a1401883f.png)

[Code here](https://github.com/SaraMesquita/PersonalVizLab/blob/main/Funnel%20Plot.ipynb)

### (2) Using Google Trends API to visualize mental health over time

<hr />

![image](![image](https://user-images.githubusercontent.com/24231383/152075890-778606e7-7295-4e9f-a651-a7381af45a07.png))

[Code here](https://github.com/SaraMesquita/PersonalVizLab/blob/main/Google%20Trends%20API_MentalHealth.ipynb)
